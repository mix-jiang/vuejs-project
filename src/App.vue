<template>
  <div id="app">
    <img src="./assets/gingerlogos.png">
    <HelloWorld/>
    <firstcomponent></firstcomponent>
  </div>

</template>

<script>
import firstcomponent from './components/firstcomponent.vue'
import HelloWorld from './components/HelloWorld'

export default {
  name: 'app',
  components: {
    HelloWorld
  },
  components: { firstcomponent }
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
