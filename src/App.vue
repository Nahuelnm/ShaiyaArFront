<template>
<div id="body">
  <div id="bar">
    <registerBar msg="registerBar"/>
  </div>
  <div id="banner">
    <img alt="Vue logo" src="./assets/logo.png" id="logo">    
  </div>
  <div id="bar">
    <navBar msg="navBar"/>
  </div>
  <div id="components">    
    <HelloWorld msg="Welcome to Your Vue.js App"/>   
  </div>
  <socialBar msg="socialBar"/>
</div>
</template>
<script>
import HelloWorld from './components/Home.vue';
import registerBar from './components/registerBar.vue';
import navBar from './components/navBar.vue';
import socialBar from './components/socialBar'
export default {
  name: 'App',
  components: {
    HelloWorld,
    navBar,
    registerBar,
    socialBar
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
  
}
img{
  width: 30%;
}
#registro{
  height: 45px;
  background-color: rgb(27, 75, 172);
  justify-content: center;
}
#banner{
  margin-top:50px;
  width: 100%;
}
#body{
 background: url(./assets/background.jpg);
 width: 100%;
 height: 100%;
 color: black;
 background-repeat: no-repeat;
 background-color:black;
 border-radius: 10px;
}
#registro{
  text-align: right;
  border-radius: 10px;
}
#components{
  margin-top: 20px;
  margin-left: 85px;
  background-color: aliceblue;
  opacity: 0.9;
  width: 90%;
  border-radius: 10px;
  text-align: left;
  
}
</style>
