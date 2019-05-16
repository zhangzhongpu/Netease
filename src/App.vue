<template>
  <div id="app">
    <img src="./assets/logo.png">
    <router-view/>
    <FootNav/>
  </div>
</template>

<script>
  import FootNav from './components/FootNav/FootNav'
export default {
  name: 'App',
  components:{
    FootNav
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
