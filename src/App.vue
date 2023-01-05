<template>
  <div id="app">
    <router-view />  
  </div>
</template>
<script>
export default {
  name: 'App',
  components: {
  },
  mounted(){
    document.title = "Shaiya-Free MMORPG";
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
  justify-content: center;
  text-align: right;
  border-radius: 10px;
}
#banner{
  margin-top:3%;
  width: 100%;
}
#body{
 background: url(./assets/background.jpg);
 background-size: 100% auto;
 width: 100%;
 height: 100%;
 color: black;
 background-repeat: no-repeat;
 background-color:black;
 border-radius: 10px;
}
#components{
  margin-top: 20px;
  margin-left: 5%;
  color: white;
  opacity: 1;
  width: 55%;
  border-radius: 10px;
  text-align: left;
  
}
#bar{
      background-size: 61% auto;
}
</style>
