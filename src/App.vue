<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <MyName name="Esther Ukandu"/>
  </div>
</template>

<script>
import MyName from './components/MyName.vue'

export default {
  name: 'App',
  components: {
    MyName
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
  font-weight: bolder;
  font-size: 3em;
}
</style>
