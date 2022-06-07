<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <HelloBis msg="Welcome to yooouuu!!!"/>
    <HelloGenua/>
    
  </div>
</template>

<script>
import HelloBis from './components/HelloBis.vue'
import HelloGenua from './components/HelloGenua.vue'


export default {
  name: 'App',
  components: {
    HelloBis,
    HelloGenua
  }
}
</script>

<style lang="scss">
* {
  margin: 0;
  border: 0;
  box-sizing: border-box;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
