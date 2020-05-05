# Gabarito

## Exercício 1 -  Tá me copiando!?

``` js
export default function() {
  return (
    <View style={styles.box}>
      <Text style={styles.frase}>React Native</Text>
    </View>
  )
}

const styles = StyleSheet.create({
  box: {
    flex: 1,
    backgroundColor: '#fff',
    alignItems: 'center',
    justifyContent: 'center',
    backgroundColor: 'black'

  },
  frase: {
    backgroundColor: 'red',
    color: 'white',
    fontSize: 25,
    fontWeight: 'bold',
    paddingVertical: 10,
    paddingHorizontal: 20,
    borderRadius: 10
  }
})
```