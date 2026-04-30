<script setup>
import { RouterLink } from 'vue-router'
import { gestisciLogin } from '../utils/code.js'

// 1. Accendiamo la funzione ed estraiamo la variabile reattiva
const { username } = gestisciLogin()
</script>

<template>
  <div class="login-container">
    <article>
      
      <!-- Inizio del riquadro di login -->
      <div class="login-box">
        
        <!-- Il titolo ora è DENTRO il riquadro -->
        <h2>Accedi a Cineva</h2>
        
        <form @submit.prevent>
          <div>
            <label for="username">Username:<br></label>
            <input 
              type="text" 
              id="username" 
              name="username"
              v-model="username"
              maxlength="20"
            >
            <p v-if="username.length > 0 && username.length < 5" class="error-msg"> Inserisci almeno 5 caratteri.</p>
          </div>

          <br>

          <div>
            <label for="password">Password:<br></label>
            <input type="password" id="password" name="password">
          </div>

          <br>

          <button type="submit" class="login-btn">Accedi</button>
        </form>
      </div>
      <!-- Fine del riquadro -->

    </article>
  </div>
</template>