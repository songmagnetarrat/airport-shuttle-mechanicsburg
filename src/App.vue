<template>
  <div id="app">
    <img class = "header_img" alt="Airport Backdrop" src="./assets/cropped-airport-67-1.jpg">
    <HelloWorld msg="Airport Shuttle Service Mechanicsburg"/>
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

@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap');

#app {
  font-family: Montserrat, Helvetica, Arial;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  margin-top: -5px;
}
.header_img {
  object-fit: cover;
  width: 100vw;  
}
</style>
