<template>
  <div id="app">
    <itune/>
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'//
import itune from './components/itune.vue'
export default {
  name: 'App',
  components: {
    //HelloWorld//
    itune
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
</style>
