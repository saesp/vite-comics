<!-- Create un nuovo progetto utilizzando Vite e Vue 3 e definite i componenti necessari per strutturare il layout come da screenshot allegato.
Quando la struttura a macroblocchi è pronta, popolate le voci di menu dinamicamente usando i data del componente.
Per oggi diamo priorità alla struttura: quando è tutto bello solido, passiamo al Sass (cioè la definizione dei dettagli del layout sempre tramite Sass)! -->

<script setup>
import { ref } from 'vue'
</script>

<template>
  <header>
    <img src="../../public/img/dc-logo.png" alt="">
    <ul>
      <li>
        <a href="#">COMICS</a>
      </li>
      <li>
        <a href="#">COMICS</a>
      </li>
      <li>
        <a href="#">COMICS</a>
      </li>
      <li>
        <a href="#">COMICS</a>
      </li>
      <li>
        <a href="#">COMICS</a>
      </li>
      <li>
        <a href="#">COMICS</a>
      </li>
      <li>
        <a href="#">COMICS</a>
      </li>
      <li>
        <a href="#">COMICS</a>
      </li>
      <li>
        <a href="#">COMICS</a>
      </li>
      <li>
        <a href="#">COMICS</a>
      </li>
    </ul>
  </header>
</template>

<style scoped>
header {
  padding: 20px;
  background-color: black;
  display: flex;
  align-items: center;
  justify-content: space-around;
}

header ul {
  display: flex;
  list-style-type: none;
  gap: 20px;
}
</style>
