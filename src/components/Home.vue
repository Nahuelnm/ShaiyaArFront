<template>
  <div class="hello">
    <table>
      <tr>
        <td id="card"> 
          <br>
          <p><strong>SHAIYA EPISODIO 5: RELIC OF MYSTRA</strong></p><br><br>
          <p>Shaiya es un impactante y sensacional juego MMORPG de fantasía que se puede jugar de manera gratuita y que sumerge a los jugadores en una guerra masiva entre las fuerzas de la Luz y de la Oscuridad.</p>
          <br><p> Shaiya permite que los jugadores busquen la gloria jugando solos o en forma colaborativa, muchos de ellos eligiendo formar poderosos gremios, capaces de atacar y vencer hasta los más grandes y feroces monstruos de Teos. Mientras los jugadores superan los retos, ellos son recompensados con nuevas armas y armaduras, que establece sus habilidades y destrezas para convertirse en poderes dominantes de Shaiya.</p>
        </td>     
        <td id="card"> 
          <iframe id ="video" width="365" height="300" src="https://www.youtube.com/embed/gtufTJBJ2ng" frameborder="0" ></iframe>
        </td>
      </tr>
      <tr>
      <td>
      </td>
      </tr>
    </table>
    <div id="card">
    <br>
        <p><strong>Combate Competitivo de Jugador vs. Jugador (PvP)</strong></p><br>
        <p>Derrota a otros jugadores para subir de rango y avanzar en la jerarquía de la facción. Obtén títulos prestigiosos, bonificaciones de stats, y beneficios adicionales que impacten a toda tu facción.</p>
        <br>
    </div>
    <div id="card">
    <br>
        <p><strong>Bendición de la Diosa</strong></p><br>
    <p>Únete a la asombrosa y masiva lucha para controlar el continente y compiter por la Bendición de la Diosa; un buff de amplia-facción que afecta a todos los miembros de tu facción, ¡aun cuando no participes en PvP!</p>
    <br><br>
    </div>

    <img alt="pvp" src="../assets/pvp.jpeg" id="pvp">
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
h3 {
  margin: 40px 0 0;
}
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
.Hello{
  text-align:left;
}
p{
  margin: 0 10px;
}
#card{
    width: 100%;
    height: 100%;
    margin-top: 20px;
    background: url(../assets/card.png);
    overflow-x:auto;
    background-size: 100% 100%;
    background-repeat: no-repeat;
    border-radius: 10px;
    justify-content: center;
    opacity:0.9;
}
#video{
  border-radius: 20px;
  opacity:1;
}
</style>
