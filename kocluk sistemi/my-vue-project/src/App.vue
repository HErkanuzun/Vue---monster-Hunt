<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <Homepage msg="Welcome to your"/>

</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Homepage from './views/Home.vue'


export default {
  name: 'App',
  components: {
    HelloWorld,
    Homepage,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: hsl(60, 81%, 51%);
  margin-top: 60px;
}
</style>
