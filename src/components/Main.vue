<!-- Create un nuovo progetto utilizzando Vite e Vue 3 e definite i componenti necessari per strutturare il layout come da screenshot allegato.
Quando la struttura a macroblocchi è pronta, popolate le voci di menu dinamicamente usando i data del componente.
Per oggi diamo priorità alla struttura: quando è tutto bello solido, passiamo al Sass (cioè la definizione dei dettagli del layout sempre tramite Sass)! -->

<script setup>
import { ref } from 'vue'
</script>

<template>
    <main class="conteiner">Content goes here</main>
</template>

<style scoped>
main {
    padding-top: 50px;
    padding-bottom: 50px;
    color: white;
    background-color: black;
}
</style>
