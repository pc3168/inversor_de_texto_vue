<template>
  <div>
    <input v-model="texto" type="text" />
    <button @click="inverter">Inverter</button>
    <p>{{ textoInvertido }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      texto: "",
      textoInvertido: "",
    };
  },
  methods: {
    inverter() {
      this.textoInvertido = this.texto.split("").reverse().join("");
    },
  },
};
</script>
