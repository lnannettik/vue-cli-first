<template>
  <div id="app">
    <Titolo/>
    <StiCazzi/>
  


  </div>
</template>

<script>
import Titolo from './components/Titolo.vue'
import StiCazzi from './components/StiCazzi.vue'

export default {
  name: 'App',
  components: {
    Titolo,
    StiCazzi


  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
