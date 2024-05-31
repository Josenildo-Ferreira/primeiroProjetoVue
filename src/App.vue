<template>
  <img alt="Vue logo" src="./assets/logoCarro.png">
  <PaginaInicial msg="Bem vindo ao site CARRO CERTO!"/>
  <GaleriaFotos/>
  <img alt="Vue logo" src="./assets/novoCorolla.webp">
  <img alt="Vue logo" src="./assets/novoOnix.webp">
  <img alt="Vue logo" src="./assets/novoVersa.webp">
  <DicasManutencao/>
  <DicaCarroNovo/>
</template>

<script>
import PaginaInicial from './components/PaginaInicial.vue'
import GaleriaFotos from './components/GaleriaFotos.vue'
import DicasManutencao from './components/DicasManutencao.vue'
import DicaCarroNovo from './components/DicaCarroNovo.vue'


export default {
  name: 'App',
  components: {
    PaginaInicial, GaleriaFotos, DicasManutencao, DicaCarroNovo
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #8e2b00;
  margin-top: 60px;
}
</style>
