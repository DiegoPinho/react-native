# Gabarito

## Exercício 1 - Divide ou não divide?

``` js
export default props =>
  <View style={styles.container}>
    {verificaDivisivel3(props.num)}
  </View>

function verificaDivisivel3(num) {
  return numero % 3 == 0
    ? <Text style={styles.text}>O número é divisível por 3</Text>
    : <Text style={styles.text}>O número não é divisível por 3</Text>
}
```

## Exercício 2 - Divide entre vários?

Crie um componente funcional que verifica se um número é divisível por 2 e 3.

``` js
export default props =>
  <View style={styles.container}>
    {verificaDivisivel2e3(props.num)}
  </View>

function verificaDivisivel2e3(num) {
  return numero % 2 == 0 && numero % 3 == 0
    ? <Text style={styles.text}>O número é divisível por 2 e 3</Text>
    : <Text style={styles.text}>O número não é divisível por 2 e 3 ao mesmo tempo</Text>
}
```