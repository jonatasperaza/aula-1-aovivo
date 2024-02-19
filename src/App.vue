<script setup>
import { ref } from 'vue'
const contador = ref(0)
function incrementar(){
  contador.value++
}
function decrementar(){
  contador.value--
}
</script>

<template>
<button @click="incrementar()">Incrementar</button>
<button @click="decrementar()">decrementar</button>
<p>O valor do contador é {{ contador }}</p>
</template>

<style scoped>

</style>
