# Gabarito

## questoes[0].resposta

A interface gráfica tanto do React como do React Native são desenvolvidas em JSX, uma extensão da sintaxe do JavaScript que lembra HTML/XML, porém é uma mistura dos dois. Nesta estrutura, conseguimos escrever HTML, CSS e JavaScript em um único arquivo. Como os componentes devem ser estruturas independentes, ou seja, seu código HTML, CSS e JavaScript devem funcionar de forma autônoma; o JSX se faz extretamente necessário. Caso contrário, teríamos que voltar a divisão tradicional de arquivos, o que não é vantajoso neste paradigma de desenvolvimento.

## questoes[1].resposta

SPA é a sigla para Single Page Application que, em tradução livre, significa Aplicação de Página Única. Na prática isso não significa que os aplicativos possuem apenas uma tela, muito pelo contrário, podem ter várias. O que acontece por debaixo dos panos é que apenas uma página é criada e seu conteúdo é trocado de forma a parecer para o usuário que são páginas diferentes, mas não são.


## questoes[2].resposta

``` javascript
class App extends React.Component {
  render() {
    return (
      <Text>Eu estou aprendendo React Native cheio de classe.</Text>
    )
  }
}
```

## questoes[3].resposta

O problema está no retorno desta função. O código escrito tenta devolver dois componentes que são adjacentes (ou seja, irmãos) e o React não consegue lidar com isso. O React oferece várias maneiras de resolvermos isso, mas o importante é saber que por via de regra a função render deve retornar sempre apenas um componente. Tendo isso em mente, conseguiríamos arrumar o código do exercício encapsulando tudo dentro do componente `<View>`.

``` js
import React from 'react';
import { Text, View } from 'react-native';

export default function App() {
  return (
    <View>
      <Text>Olá mundo!</Text>
      <Text>Este é o meu primeiro aplicativo!</Text>
    </View>
  )
}
```

## questoes[4].resposta

Sabe aquele tipo de discussão inútil entre devs? Este é um bom exemplo. Dentro do contexto, os dois desenvolvedores estão certos, é somente uma questão de preferência.
