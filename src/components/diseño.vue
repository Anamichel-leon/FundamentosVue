<template>
    <div class="cloud-container">
      <h1 class="restaurant-name">RESTAURANTE ALMA DE TLAXIACO</h1>
    </div>
  </template>
  
  <style scoped>
  /* Contenedor con imagen en alta resolución */
  .cloud-container {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 20vh;
    width: 100%;
    background: url('https://i.pinimg.com/originals/e3/65/86/e36586168a851e8901e315d847a6e042.jpg') no-repeat center center;
  background-size: cover; /* Ajuste de imagen para mayor calidad */
  image-rendering: crisp-edges; /* Intenta mejorar la nitidez */
}
  
  /* Estilo del texto */
  .restaurant-name {
    font-size: 26px;
    color: white;
    font-weight: bold;
    background: linear-gradient(45deg, #6db3f2, #1e3c72);
    padding: 20px 30px;
    border-radius: 50px;
    box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.2);
  }
  </style>
  