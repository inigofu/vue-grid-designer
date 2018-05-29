<template>
  <div id="app">
    <griddesigner/>
  </div>
</template>

<script>
import griddesigner from './components/gridDesigner'

export default {
  name: 'App',
  components: {
    griddesigner
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
}
</style>
