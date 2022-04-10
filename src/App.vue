<template>
  <portfolio_home msg="Welcome to Glory's Portfolio"/>
</template>

<script>
import portfolio_home from './components/portfolio_home.vue'

export default {
  name: 'App',
  components: {
    portfolio_home
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #fff;
  background-color: #404040;
}
</style>
