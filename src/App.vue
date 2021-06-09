<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <hr/>
    <MiComponte></MiComponte>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import MiComponte from './components/MiComponte.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    MiComponte
  }
}
</script>

<style>

@import './assets/css/styles.css'
</style>
