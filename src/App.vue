<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <Hello />
    <Cars name="peugeot" model="206" year= "2002"/>
    <CarPage /> 
  </div>
</template>

<script>
import Hello from './components/HelloWorld.vue'
import Cars from './components/Cars.vue'
import CarPage from './pages/CarPage.vue'

export default {
  name: 'app',
  components: {
    Hello,Cars, CarPage
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
