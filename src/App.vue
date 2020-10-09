<template>
  <div id="app">
    
    <Home/>
    <Content/>
    <!-- <Home  msg=" "/> -->
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import Home from './components/Home.vue'
import Content from './components/content'
export default {
 
  components: {
  //  HelloWorld,
    Home,
    Content

  }
}
</script>

<style>
*{
  margin:0;
  padding:0;
}
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */
</style>
