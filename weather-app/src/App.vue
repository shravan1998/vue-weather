<template>

  <router-view></router-view>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
  //  HelloWorld
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@300;400&display=swap');
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif,Roboto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  
  color: white;
  margin-top: 60px;
}
*{
  background: #2A2441;
}
</style>
