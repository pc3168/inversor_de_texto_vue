<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Bem Vindo ao meu App Vue.js, primeiro Inversor de Texto"/>
  <InversorTexto />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import InversorTexto from './components/InversorTexto.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
    InversorTexto
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2664a3;
  margin-top: 60px;
}
</style>
