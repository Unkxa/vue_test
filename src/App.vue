<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <Hi/>
    <H2/>
    <H2/>
    <H2/>
    <h2> mjsklfkl</h2>
  </div>
</template>

<script>
import H2 from './components/H2.vue'
import HelloWorld from './components/HelloWorld.vue'
import Hi from './components/hi.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Hi,
    H2
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
