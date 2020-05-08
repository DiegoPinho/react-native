# Exercícios

## questoes[0].titulo = "JS eu conheço, mas JSX? Isso é um jogo?"

O React trabalha com uma estrutura de arquivos chamada de JSX.
Quais as vantagens desta estrutura? Por que precisamos dela?

## questoes[1].titulo = "SPA? Eu quero uma massagem..."

Dizemos que o React/React Native são tecnologias Single Page Application (SPA).
Na prática, o que isso significa?

## questoes[2].titulo = "Se exibindo para todos"

Crie um componente funcional que exibe na tela do celular a frase: `Eu estou aprendendo React Native.`
Use o componente nativo `<Text>`.


## questoes[3].titulo = "Cuidado com esse retorno!"

Um desenvolvedor escreveu o seguinte trecho de código para o seu aplicativo em React Native.

``` js
import React from 'react';
import { Text } from 'react-native';

export default function App() {
  return (
    <Text>Olá mundo!</Text>
    <Text>Este é o meu primeiro aplicativo!</Text>
  )
}
```

No entanto, na hora de executá-lo no Expo, o seguinte erro é exibido.

``` bash
Adjacent JSX elements must be wrapped in an enclosing tag. Did you want a JSX fragment <>...</>
```

Qual é a causa deste problema? Como resolvê-lo?

## questoes[4].titulo = "Classes? Mas isso é escola, por acaso!?"

No React podemos trabalhar com dois formatos de componentes: classe e funcional. No uso dos componentes de classe, dois desenvolvedores entraram em debate. O primeiro acredita que os componentes de classe devem ser inicializados da seguinte maneira:

``` js
import React from 'react';

class Componente extends React.Component {
  //...
}

export default Componente;
```

Ou segundo acredita que o código correto é este:


``` js
import {Component} from 'react';

class Componente extends Component {
  //...
}

export default Componente;
```

Quem está certo?
