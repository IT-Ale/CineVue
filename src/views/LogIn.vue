<script setup>
import { RouterLink } from 'vue-router'
</script>

<template>
  <div class="login-container">
    <article>
      <h2>Accedi a Cineva</h2>
      <form>
        <div>
          <label for="username">Username:<br></label>
          <input type="text" id="username" name="username">
        </div>

        <br>

        <div>
          <label for="password">Password:<br></label>
          <input type="password" id="password" name="password">
        </div>

        <br>

        <button type="submit">Accedi</button>
      </form>
    </article>
  </div>
</template>
