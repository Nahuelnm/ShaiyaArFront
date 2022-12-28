<template>
<div id="introblock">  
  <div id="item1">  
    ¡Gana un Paquetazo!
   <p id="description">¡Gasta APs por la 1ª vez y gana <br> gratis el Paquete Primera Compra!</p>
   <div id="item2">  
    Historia
    <p id="description">Entérate de todo acerca del <br>mundo de Shaiya</p>


  </div>
  <div id="item3">  
    Preguntas/Respuestas
    <p id="description">Halla aquí respuestas a tus <br>preguntas de Shaiya...</p>

  </div>
  </div>

  <div id="video">
    <iframe id ="video" width="365" height="300" src="https://www.youtube.com/embed/gtufTJBJ2ng" frameborder="0" ></iframe>
  </div>
  

</div>

</template>

<script>
export default {
  name: 'introBlock',
  props: {
    msg: String
  }
}
</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#introblock{
  width: 600px;
  height: 333px;
  margin-left: 4%;
  background: url(../assets/08-13-shaiya-intro-block.png);
  font-weight: bold;
  color: #ffd797;
  background-size: 100% 100%;
  background-repeat: no-repeat;
  float:left;

}
#item1 {
  margin-left: 3%;
  margin-top: 20px;
  padding:0%;
  font-size: 10px;
  text-align: left;
  float:left;
}
#item2 {
  margin-left: 0%;
  margin-top: 50px;
  font-size: 10px;
  text-align: left;
}
#item3 {
  margin-left: 0%;
  margin-top: 33px;
  font-size: 10px;
  text-align: left;
}
#video {
  margin-top: 5px;
  margin-right: 2%;
  float:right;
}
</style>
