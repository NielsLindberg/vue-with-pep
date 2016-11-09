<template>
  <div id="app">
    <dragger></dragger>
  </div>
</template>

<script>
import Dragger from './components/Dragger'
export default {
  name: 'app',
  components: {
    Dragger
  }
}
</script>

<style>
html, body {
  overflow: hidden;
  background-color: #6f8197;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
