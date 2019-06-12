<template>
  <div>
     <h2>wefsd  dfdff</h2>
      <p>{{test}} | {{getGret}}</p>
  </div>
 
</template>

<script>
export default {
 data(){
    return{
      test: 'red',
      test2: 'test2'
    }
 },
 computed: {
    getGret(){
      return  this.test.split("").reverse().join("")
    } 
 },
  name: 'HelloWorld',
  props: {
    msg: String ,
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">


h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
