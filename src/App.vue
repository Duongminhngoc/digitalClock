<template>
  <div id="app">
    <DigitalClock msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import DigitalClock from './components/DigitalClock.vue'

export default {
  name: 'App',
  components: {
    DigitalClock
  }
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
#app {
  background: radial-gradient(ellipse at center,  #0a2e38  0%, #000000 70%);
  width: 100%;
  height: 100vh;
}
</style>
