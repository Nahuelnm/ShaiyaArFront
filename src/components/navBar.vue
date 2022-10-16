<template>
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
      <th id="download">  DESCARGA</th>
    </tr>
    </table>
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
  #tabla{
    width: 90%;
    margin-top: 10px;
    padding: 0;
    margin-left: 350px;
    line-height: 60px;
    color: white;
    font-size: 14px;
    display: flex;
    text-align: left;
    justify-content: left;
    border-spacing: 32px;
    border-collapse: separate;
    background: url(../assets/frame-header.png);
    background-repeat: no-repeat;
  }
  #download{
    color: black;
    font-size: 25px;
    text-align: right;
  }

</style>
