<template>
  <h1>{{ title }}</h1>
  <button v-on:click="activarBoton" class="btn btn-primary m-2">
    Activame 1
  </button>
  <button @click="activarBoton" class="btn btn-danger m-2">Activame 2</button>
</template>

<script setup>
const title = 'Vite + Vue';
//metodo
const activarBoton = () => {
  console.log('me activaste');
};
</script>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
