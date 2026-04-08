<script setup>
import { RouterLink } from 'vue-router'
</script>

<template>
  <header>
    <RouterLink to="/">
      <img src="../assets/img/logo.png" alt="Logo Cineva" width="200">
    </RouterLink>
    <hr>
    </header>
  <nav>
    <h3>Menu di navigazione</h3>
    <ul>
      <li><RouterLink to="/about">About</RouterLink></li>
      <li><RouterLink to="/contacts">Contacts</RouterLink></li>
      <li><RouterLink to="/rankings">Rankings</RouterLink></li>
      <li><RouterLink to ="/newReview">New Review</RouterLink></li>
    </ul>
    <hr>
  </nav>
  
</template>