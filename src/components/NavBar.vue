<script setup>
import { RouterLink } from 'vue-router'
</script>

<template>
  <nav>
    <ul>
      <li><RouterLink to="/about">About</RouterLink></li>
      <li><RouterLink to="/contacts">Contacts</RouterLink></li>
      <li><RouterLink to="/rankings">Rankings</RouterLink></li>
      <li><RouterLink to ="/newReview">New Review</RouterLink></li>
      <li><RouterLink to ="/logIn">Log In</RouterLink></li>
    </ul>
  </nav>
</template>