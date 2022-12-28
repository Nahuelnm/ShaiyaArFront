<template>
  <div id="separator">
    
  </div>
  <div id="notice">
    <h2>Noticias</h2>
    <h5>Apertura del servidor Shaiya Argentina</h5>
    <h2>Eventos</h2>
    <h5>No hay eventos programados por el momento.</h5>
  </div>
  <div id="eventos">

  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}

p{
  margin: 0 10px;
}

#notice{
  width: 600px;
  height: 1000px;
  margin-left: 4%;
  font-weight: bold;
  color: #ffd797;
  background-repeat: no-repeat;
}
</style>
