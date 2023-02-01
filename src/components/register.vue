<template>
  <div id="registerSh">
    <div id="title">
    <h3>  Regístrate - ¡Juega Gratis!    </h3>
    </div>
    <form action="" target="_blank">
      <p id="user">Tu Usuario: <input type="text" name="nombrecompleto">  </p>
        <p id="pass">Tu Contraseña: <input type="text" name="nombrecompleto"> </p>
        <p> ¿Ya tienes cuenta? ¡Inicia sesión ahora! </p>
        <input type="submit" value="¡Regístrate y Juega!" id="submit">

  </form>
 </div>
</template>





<script>
export default {
  name: 'registerSh',
  props: {
    msg: String
  }
}
</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#registerSh{
  width: 512px;
  height: 458px;
  margin-top: 10%;
  margin-left: 33%;
  color: #ffd797;
  background-repeat: no-repeat;
  box-shadow: 0px 0px 5px 1px black;
}
#title{
background: linear-gradient(#5195f5, #4c8ef0);
color: #ffffff;
text-align: center;
height:50px;
display: flex;
box-shadow: 0px 0px 2px 1px black;
}
h3 {
  color:#ffff;
  font-weight: bold;
  text-shadow: 0px 2px 7px rgb(0, 0, 0);
  margin-left: 30%;
}
h5 {
  margin-top: 50px;
  color:#9c9caa;
  font-weight: bold;
  font-style : oblique;
  
}
p{
  margin: 0 px;
  color:#070707;
font-size: 15px;
}
input{
 
}
#user{
  margin-left: 5%;
}
#pass{
  margin-left: 0.5px;
}
#submit{
  margin-left: 55%;
  background-color: #4c8ef0;
  color: #ffffff;
  width: 40%;
  height: 30px;
  border-radius: 4px;
  font-size: 15px;
  border-style: none ;
  box-shadow: 0px 0px 2px 1px black;

}
</style>
