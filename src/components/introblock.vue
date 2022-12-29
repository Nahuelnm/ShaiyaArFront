<template>
<div id="introblock">  
  <div id="item1">  
  <h2> ¡Gana un Paquetazo!</h2>
   <p id="description">¡Gasta APs por la 1ª vez y gana <br> gratis el Paquete Primera Compra!</p>
   <div id="item2">  
    <h2>  Historia </h2> 
    <p id="description">Entérate de todo acerca del <br>mundo de Shaiya</p>


  </div>
  <div id="item3">  
    <h2> Preguntas/Respuestas</h2>
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
  line-height: 0.1em;
  text-align: left;
  float:left;
}
#item2 {
  margin-left: 0%;
  margin-top: 55px;
  font-size: 10px;
  text-align: left;
  line-height: 0.1em;
}
#item3 {
  margin-left: 0%;
  margin-top: 35px;
  font-size: 10px;
  text-align: left;
  line-height: 0.1em;
}
#video {
  margin-top: 4px;
  margin-right: 0.8%;
  width: 390px;
  height: 319px;
  float:right;
}
p {
  color: #fff4d8;
  line-height: 1.2;
}
</style>
