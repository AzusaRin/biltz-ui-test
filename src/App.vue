<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <bl-button>nihao</bl-button>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import { Button } from 'blitz-ui-demo'

export default {
  name: 'App',
  components: {
    HelloWorld,
    'bl-button':Button
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
