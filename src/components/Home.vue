<template>
  <div id="separator">
    
  </div>
  <div id="notice">
    <div><img alt="block news" src="../assets/08-13-shaiya-block-news.png" id="blockNews">   </div>
    <h2>Noticias</h2>
    <h5>Apertura del servidor Shaiya Argentina</h5>
    <div>
      <hr>  <br>
    </div>
    <h2>Eventos</h2>
    <h5>No hay eventos programados por el momento.</h5>
    <div>
      <hr>  <br>
    </div>
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
  color: #ffd797;
}

p{
  margin: 0 px;
}
h2 {
  line-height: 0.1em;
  color: #74110f;
  margin-top: 0.1px;
}
h5 {
  color: #ffc861;
  margin-top: 50px;
}
#notice{
  width: 600px;
  height: 1000px;
  margin-left: 4%;
  font-weight: bold;
  color: #ffd797;
  background-repeat: no-repeat;
}
hr {
  border-color: #3b2808;
  width: 90%;
  margin-left: 0.1%;
}
#blockNews {
  margin-top: 30px;
  width: 96%;
}
</style>
