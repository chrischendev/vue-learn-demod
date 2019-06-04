<template>
  <div id="app">
    <img src="./assets/logo.png">
    <ChrisComp/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld'
import ChrisComp from './components/ChrisComponent'

export default {
  name: 'App',
  components: {
    ChrisComp
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
