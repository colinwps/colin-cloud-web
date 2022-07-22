<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <UserSelect departmentName="test"></UserSelect>
  </div>
</template>

<script>
import UserSelect from './components/UserSelect.vue'

export default {
  name: 'App',
  components: {
    UserSelect
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
