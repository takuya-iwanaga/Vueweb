<template>
  <div id="app">
    <app-header></app-header>
    <HelloWorld/>
    <app-footer></app-footer>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import header from './components/Header.vue'
import footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    'app-header': header,
    HelloWorld,
    'app-footer': footer,
  }
}
</script>

<style>
#app {
  background: url("assets/back.jpg");
  background-size: cover;
  background-position: center;
  width: auto;
  height: auto;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
