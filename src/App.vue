<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <MyHome msg="Vue js 프로젝트 만들기"/>
  </div>
</template>

<script>
import MyHome from './components/MyHome.vue'

export default {
  name: 'App',
  components: {
    MyHome
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
