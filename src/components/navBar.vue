<template>

 <nav id="menu">
  <ul id="menu_items">
    <li>COMUNIDAD</li>
    <li>ACERCA DE SHAIYA</li>
    <li>MULTIMEDIA</li>
    <li>TIENDA</li>
    <li>SERVICIOS GM</li>
    <li></li><li></li><li></li><li></li>
    <li id="download">Descargar<br>Juega Gratis</li>
  </ul>
 </nav> 
</template>

<script>
export default {
  name: 'navBar',
  props: {
    msg: String
  }
}
</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  #menu{
    background: url(../assets/frame-header.png);
    background-size: 70% auto;
    background-repeat: no-repeat;
    width: 100%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    color: #ffd797;
    font-weight: bold;



    margin-top: 10px;
    padding: 10px;
    margin-left: 0%;
    line-height: 60px;
    font-size: 14px;
    overflow-x:auto;


  }
  #download{
    margin-top: 0;
    line-height: 100%;
    color: #ac3d1c;
    margin: 200px;
    font-size: 30px;
  }
  #menu_items{
    display: flex;
    list-style: none;
  }

  #menu_items li{
    border-radius: 3px;
    margin: 10px 14px;
  }
</style>
