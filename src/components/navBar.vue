<template>
 <div id="menu">
    <div id="community">
      <H5>COMUNIDAD</H5>
    </div>
    <div id="about">
      <H5>ACERCA DE SHAIYA</H5>
    </div>
    <div id="multimedia">
      <H5>MULTIMEDIA</H5>
    </div>
    <div id="store">
      <H5>ALMACÉN DE ARTÍCULOS</H5>
    </div>
    <div id="store">
      <H5>SERVICIOS GM</H5>
    </div>
    <div id="download">
      <H1>Descargar</H1><H3>Juega Gratis</H3>
    </div>

  </div>
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
    background-size: 100% 90%;
    background-repeat: no-repeat;
    width: 70%;
    height:110px;
    display: flex;
    align-items: center;
    color: #ffd797;
    font-weight: bold;
    vertical-align: middle;
    margin-top: 10px;
    padding: 0.2%;
    margin-left: 0%;
    overflow-x:auto;
    line-height: 120%;

  }
  #community{
    margin-left:5%;

  }
  #about{
    margin-left:2%;

  }
  #multimedia{
    margin-left:2%;

  }
  #store{
    margin-left:2%;

  }
  #download{
    margin-left:9.2%;
    text-align: center;
    color: #ac3d1c;
    line-height: 0.1em;
  }
</style>
