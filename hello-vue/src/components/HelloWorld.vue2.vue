<template>
  <div id="app">
      <img alt="Vue logo" src="./assets/logo.png">
      <HelloWorld msg="Hi ITEC-2560 Student, Welcome to Your Vue.js App"/>
  </div>
      </template>


<script>
import HelloWorld from './components'

export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
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
