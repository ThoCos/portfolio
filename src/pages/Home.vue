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
      <RouterLink to="/about" class="btn btn-primary btn-lg"
        >Me contacter</RouterLink
      >
    </div>
  </div>
</template>
