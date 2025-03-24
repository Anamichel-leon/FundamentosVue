<script setup>

import Card from './Card.vue';
import carrusel from './carrusel.vue';
import diseño from './diseño.vue';



import Footer from './Footer.vue'; 
import Navbar from './Navbar.vue';
</script>

<template>

  <div class="container">
    <diseño />

    
    <Navbar/>
    

    
    <carrusel/>
    

    <!-- Primer row -->
    <Card/>
    
    <!-- Footer -->
    <Footer/>

  </div>
</template>

<style scoped>
/* Agrega tus estilos personalizados aquí */
</style>
