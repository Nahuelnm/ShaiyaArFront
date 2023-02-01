<template>
  <div id="registro">
    <table >
    <tr>
      <th></th>
      <th id="epi">  EPISODIO 5.4</th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>

      <th id="singUp"><a v-bind:href="'/signup'"><button id="button">¡Regístrate!</button></a></th>
      <th id="login"><button id="button">Iniciar sesión</button> </th>    
      <th></th>
    </tr>
    </table>
  </div>
</template>

<script>
export default {
  name: 'registerBar',
  props: {
    msg: String
  }
}
</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#registro{
    padding: 0;
    width:50%;
    line-height: 40px;
    margin-left: 27%;
    color: white;
    font-size: 14px;
    display: flex;
    text-align: right;
    justify-content: right;
    border-spacing: 10px;
    border-collapse: separate;
    background-repeat: no-repeat;

}
#button{
  background: linear-gradient(#ffffff, #c0bfbc);
  border-color: dimgray;
  font-size: 13.6px;
  padding-top:4.5px; 
  padding-bottom:4.5px;
  border-radius: 4px;
  border-width:1px;
}
</style>
