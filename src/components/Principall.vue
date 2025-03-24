<script setup>
import Card from './Card.vue';
import CardPrincipal from './CardPrincipal.vue';

import Footer from './Footer.vue'; 
import Navbar from './Navbar.vue';
</script>

<template>
  <div class="container">
    <Navbar/>
    <h1 class="text-center">RESTAURANTE</h1>

    <CardPrincipal/>
    

    <!-- Primer row -->
    <Card/>
    
    <!-- Footer -->
    <Footer/>

  </div>
</template>

<style scoped>
/* Agrega tus estilos personalizados aquí */
</style>
