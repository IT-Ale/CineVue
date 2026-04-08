<script setup>
import { RouterView } from 'vue-router'
import Header from './components/Header.vue' 
import Footer from './components/Footer.vue'
</script>

<template>

  <Header /> 
  
  <hr>

  <div class="main-content">
    <RouterView />
  </div>

  <Footer />

</template>