<template>
  <div>
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Nothing here, yet..."/>
  </div>
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
  color: lch(89.82% 33.94 166.82);

  background-image: url('./assets/background.jpg'); /* or ./assets/background.jpg */
  background-size:cover;
  background-position: center;
  background-repeat: no-repeat;
  min-height: 100vh;
}
</style>
