<script setup>
import { RouterLink } from 'vue-router';
</script>

<template>
  <div class="jumbotron">
    <div class="container">
      <h1 class="display-4">Portfolio</h1>
      <p class="lead">
        Bienvenue sur mon portfolio !
      </p>
      <h2>Mes projets</h2>

      <div id="carouselExampleAutoplaying" class="carousel slide" data-bs-ride="carousel">
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="img/asperges_tc.jpg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="img/CustomPasta.jpg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="img/redesign_rolex.png" class="d-block w-100" alt="...">
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleAutoplaying" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleAutoplaying" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>
      <br>
      <RouterLink to="/about" class="btn btn-primary btn-lg"
        >Me contacter</RouterLink
      >
    </div>
  </div>
</template>
