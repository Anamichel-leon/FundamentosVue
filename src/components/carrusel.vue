<template>
  <div class="background-container">
    <div class="carousel-wrapper">
      <div id="carouselExampleControls" class="carousel slide carousel-container" data-bs-ride="carousel" data-bs-interval="3000">
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img 
              src="https://img.freepik.com/vector-gratis/logo-restaurante-retro_23-2148490227.jpg?semt=ais_hybrid" 
              class="d-block w-100" 
              alt="Carta de restaurante vintage">
          </div>
          <div class="carousel-item">
            <img 
              src="https://img.freepik.com/premium-vector/fast-food-neon-sign_191108-234.jpg?w=360" 
              class="d-block w-100" 
              alt="Carta de restaurante vintage">
          </div>
          <div class="carousel-item">
            <img 
              src="https://th.bing.com/th/id/OIP.Ighrj49jIOTN7cq-UHfeLgHaHa?rs=1&pid=ImgDetMain" 
              class="d-block w-100" 
              alt="Carta de restaurante vintage">
          </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>
    </div>
  </div>
</template>

<style scoped>
/* Contenedor con imagen de fondo */
.background-container {
  background-image: url('https://i.makeagif.com/media/11-09-2015/6DoRko.gif'); 
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  height: 80vh; 
  display: flex;
  justify-content: center; 
  align-items: center; 
}

.carousel-wrapper {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
  height: auto;
}

.carousel-container {
  width: 515px; 
  height: auto;
}
</style>