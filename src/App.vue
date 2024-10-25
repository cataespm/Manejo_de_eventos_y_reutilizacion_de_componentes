<script setup>
import { RouterView } from 'vue-router'
</script>

<template>
  <nav class="navbar navbar-expand-lg bg-light border-radius">
    <div class="container-fluid">
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <RouterLink class="nav-link text-grey" :to="{ name: 'home' }">Home</RouterLink>
          </li>
          <li class="nav-item">
            <RouterLink class="nav-link text-grey" :to="{ name: 'contact' }">Contacto</RouterLink>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <RouterView />
</template>
<style scoped></style>
