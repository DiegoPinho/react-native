# Gabarito

## Exercício 1 - Usando os poderes de mais de 8000 do Flexbox

``` js
export default function() {
  return (
    <View style={styles.box1}>
        <View style={styles.box2}/>
        <View  style={styles.box3} />
        <View  style={styles.box4}/>
    </View>
  )
}

const styles = StyleSheet.create({
  box1: {
    flex: 1,
    flexDirection: 'column',
    justifyContent: 'center',
    alignItems: 'stretch',
  },
  box2: {
    width: 50,
    height: 50, 
    backgroundColor: 'powderblue’,
  }, 
  box3: {
    height: 50, 
    backgroundColor: 'skyblue'.
  },
  box4: {
    height: 100, 
    backgroundColor: 'steelblue'
  }
})
```

# Exercício 2 - Usando os poderes de mais de 8000 do Flexbox pela segunda vez

``` js
class FlexBoxPower extends React.Component {
render() {
  return (
      <View style={styles.container}>  
        <View style={styles.box1} />  
        <View style={styles.box2} />  
        <View style={styles.box3} />  
      </View>  
    );  
  }  
}  

const styles = StyleSheet.create({  
  container: {
    flex: 1,
    flexDirection: 'column',
    justifyContent: 'center',
    alignItems: 'stretch'
  },
  box1: {
    width: 60,  
    height: 60,  
    backgroundColor: 'powderblue'  
  },
  box2: {
    width: 60,  
    height: 60,  
    backgroundColor: 'skyblue'
  },
  box3:{  
    height: 60,  
    backgroundColor: 'steelblue'
  }
})

```



