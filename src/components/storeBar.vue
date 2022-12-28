<template>
<div id="storeBar">  
  <p>ARTÍCULOS & NOVEDADES</p>
<div>
  <img alt="art1" src="../assets/craft.gif" id="art"> <br><p id="articulo">Paquete de lapises STATS</p>
  <div id="priceConteiner"><br><p id="price">199AP<img alt="art1" src="../assets/ap_32x32.png" id="ap"></p></div>   
</div>
<div>
  <hr>  <br>
</div>
<div>   
  <img alt="art1" src="../assets/EarthDay.png" id="art"><br><p id="articulo">Paquete de lapises Elementales</p>
  <div id="priceConteiner"><br><p id="price">199AP<img alt="art1" src="../assets/ap_32x32.png" id="ap"></p></div>   
</div> 
<div>
  <hr>  <br>
</div>
<div>   
  <img alt="art1" src="../assets/freedom_icon.png" id="art"><br><p id="articulo">Paquete Sorpresa</p>
  <div id="priceConteiner"><br><p id="price">199AP<img alt="art1" src="../assets/ap_32x32.png" id="ap"></p></div>   
</div> 
<div>
  <hr>  <br>
</div>
<div >
  <th id="singUp"><button id="button">Regístro Gratuito</button> </th>
</div>
<div>
  <br>
  <hr>
  <br>
</div>
</div>

</template>

<script>
export default {
  name: 'storeBar',
  props: {
    msg: String
  }
}
</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#storeBar{
  width: 300px;
  float:right;
  margin-right: 32.5%;
  background: url(../assets/store_background.png);
  font-weight: bold;
  color: #ffd797;
  background-size: 100% 100%;
  background-repeat: no-repeat;

}
#art{
  width: 60%;
  margin-left: 5%;
  background: url(../assets/store_background.png);

  color: #ffffff;

}
#ap{
  vertical-align: middle;
  width: 32px;
  height: 32px;
}
#articulo{
  padding-top:4.5px; 
  color: #ffffff;
}

#price{
  color: #ffd797;
  font-size: 12px;
  text-align: left;
  margin-left:20%;
}
hr {
  border-color: #3b2808;
  width: 70%;
}
#button{
  background:#161311;
  border-color:#922121;
  font-size: 15px;
  padding-top:4.5px; 
  padding-bottom:4.5px;
  border-radius: 4px;
  border-width:1px;
  width: 70%;
  color: #922121;
    
}
</style>
