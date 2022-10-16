<template>
  <div class="hello">
    <br>
    <p>Shaiya es un impactante y sensacional juego MMORPG de fantasía que se puede jugar de manera gratuita y que sumerge a los jugadores en una guerra masiva entre las fuerzas de la Luz y de la Oscuridad.</p>
    <p> Shaiya permite que los jugadores busquen la gloria jugando solos o en forma colaborativa, muchos de ellos eligiendo formar poderosos gremios, capaces de atacar y vencer hasta los más grandes y feroces monstruos de Teos. Mientras los jugadores superan los retos, ellos son recompensados con nuevas armas y armaduras, que establece sus habilidades y destrezas para convertirse en poderes dominantes de Shaiya.</p>
    <br>

  </div>

  <div id="banner">
    <img alt="vs" src="../assets/home.png" id="vs">    
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
</style>
