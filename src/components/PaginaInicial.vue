<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      Aqui você confere as melhores dicas para escolher seu carro novo!,<br>
      Confira o link:
      <a href="https://www.youtube.com/watch?v=BRmuIeSqyKo" target="_blank" rel="noopener">Canal "Opinião Sincera"</a>.<br>
      (link de vídeo aleatório - apenas para fins acadêmicos).
    </p>
    <h3>Confira abaixo o review dos carros mais vendidos</h3>
    <ul>
      <li><a href="https://www.youtube.com/watch?v=Hf-zQCyrBss&t=110s" target="_blank" rel="noopener">Nissan Versa</a></li>
      <li><a href="https://www.youtube.com/watch?v=HmIZ5CPwHCs" target="_blank" rel="noopener">Onix</a></li>
      <li><a href="https://www.youtube.com/watch?v=-E4Uu1eKBRE" target="_blank" rel="noopener">Corolla</a></li>
    </ul>   
  </div>
</template>

<script>
export default {
  name: 'PaginaInicial',
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
