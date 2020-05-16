<template>
  <div id="app">
    <img src="./assets/logo.png">
    <AppComponent/>
  </div>
</template>

<script>
import AppComponent from './components/AppComponent'

export default {
  name: 'App',
  components: {
    AppComponent
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
  margin-top: 60px;
}
</style>
