<template>
  <div class="hello">
    
    <h3>Confira as nossas melhores dicas de manutenção</h3>
    <ul>
      <li><a href="https://www.youtube.com/watch?v=au97pDuFmJU" target="_blank" rel="noopener">Como trocar o óleo do motor</a></li>
      <li><a href="https://www.youtube.com/watch?v=mA6Db-FCgVg" target="_blank" rel="noopener">Hora de trocar pneus?</a></li>
      <li><a href="https://www.youtube.com/watch?v=Yiy1_q7N1TQ" target="_blank" rel="noopener">Como trocar pastilhas de freio</a></li>
    </ul>   
  </div>
</template>

<script>
export default {
  name: 'DicasManutencao',
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
</style>
