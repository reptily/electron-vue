<template>
  <img alt="Vue logo" src="./assets/logo-vue.png">
  <span class="plus">+</span>
  <img alt="Vue logo" src="./assets/logo-electron.png">
  <HelloWorld msg="Welcome to Your Vue.js + Electron.js App"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
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

.plus {
  font-size: 260px;
  font-weight: bold;
  margin: 0px 30px 0px 10px;
}
</style>
