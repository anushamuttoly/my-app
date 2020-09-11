<template>
  <div id="app">
    <img alt="DHWANI" src="https://m.media-amazon.com/images/M/MV5BNjMxMzMwMzQtZDAzZC00NGMzLTk2OWMtNjkzMTY5NTU1NDJiXkEyXkFqcGdeQXVyNDQxNjcxNQ@@._V1_SY1000_CR0,0,984,1000_AL_.jpg">
    <HelloWorld msg="HelloWorld"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #00ff00;
  margin-top: 60px;
}
</style>
