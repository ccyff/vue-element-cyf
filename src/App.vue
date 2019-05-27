<template>
  <div id="app">
    <img src="./assets/logo.png">
    <biao/>
  </div>
</template>

<script>
import biao from './components/table'

export default {
  name: 'app',
  components: {
    biao
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  background-color:#d6d6d6;
  color: #2c3e50;
  padding: 60px 0;
}
#app #biao{
  width:800px;
  margin:30px auto;
  padding:20px;
}
</style>