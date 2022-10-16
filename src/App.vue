<template>
<div id="body">
 <div id="registro">
    <button>Registrarse!</button> 
    <button>Iniciar sesión</button> 
  </div>
  <div id="banner">
    <img alt="Vue logo" src="./assets/logo.png" id="logo">    
  </div>
  <div id="bar">
  <table id="tabla">
  <tr id="container">
    <th></th>
    <th></th>
    <th id="comunity">  COMUNIDAD</th>
    <th id="about"> ACERCA DE SHAIYA</th>
    <th id="multimedia">  MULTIMEDIA</th>
    <th id="store"> TIENDA</th>
    <th id="services">  SERVICIOS GM</th>
    <th></th>
    <th></th>
    <th></th>
    <th id="download">  DESCARGA</th>
  </tr>
</table>
  </div>
  <div id="components">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</div>
</template>

<script>
import HelloWorld from './components/Home.vue'

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
  color: #2c3e50;
  
}
img{
  width: 30%;
}
#registro{
  height: 45px;
  background-color: rgb(79, 39, 189);
  justify-content: center;
}
#banner{
  width: 100%;
}
#tabla{
  width: 100%;
  margin-top: 10px;
  padding: 0;
  margin-left: 250px;
  line-height: 60px;
  color: white;
  font-size: 14px;
  display: flex;
  text-align: left;
  justify-content: left;
  border-spacing: 32px;
  border-collapse: separate;
  background: url(./assets/frame-header.png);
  background-repeat: no-repeat;
}
#download{
  color: black;
  font-size: 18px;
  text-align: right;
}

#body{
 margin-left: 80px;
 background: url(./assets/background.jpg);
 width: 100%;
 height: 100%;
 color: black;
}
#registro{
  text-align: right;
}
#components{
  margin-left: 180px;
  background-color: aliceblue;
  opacity: 0.8;
  width: 80%;
}
</style>
