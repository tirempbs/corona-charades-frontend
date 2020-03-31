<template>
  <div id="app">
    <NewGame msg="Welcome to Corona Charades"/>
  </div>
</template>

<script>
import NewGame from './components/NewGame.vue'

export default {
  name: 'App',
  components: {
    NewGame
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
}
</style>
