<script setup>
import { RouterLink } from 'vue-router'
</script>

<template>
  <!-- Titolo a larghezza intera come in AboutView -->
  <div class="col-12">
    <h1>Classifiche e Ranking</h1>
  </div>

  <!-- Spazio vuoto a sinistra per centrare i contenuti -->
  <aside class="col-3"></aside>

  <!-- Contenuto principale al centro -->
  <article class="col-6">
    <h4 class="review-title">Leaderboard - Attori più apprezzati</h4>
    
    <table style="width: 100%;">
      <thead>
        <tr>
          <th>Pos.</th>
          <th>Attore</th>
          <th>Voti</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td><b>1</b></td>
          <td><RouterLink to="/attore/demi-moore">Demi Moore</RouterLink></td>
          <td>1000</td>
        </tr>
        <tr>
          <td><b>2</b></td>
          <td><RouterLink to="/attore/andrew-garfield">Andrew Garfield</RouterLink></td>
          <td>990</td>
        </tr>
        <tr>
          <td><b>3</b></td>
          <td><RouterLink to="/attore/emma-stone">Emma Stone</RouterLink></td>
          <td>700</td>
        </tr>
        <tr>
          <td><b>Altri</b></td>
          <td><RouterLink to="/attore/bradley-cooper">Bradley Cooper</RouterLink></td>
          <td>750</td>
        </tr>
        <tr>
          <td><b>Altri</b></td>
          <td><RouterLink to="/attore/lady-gaga">Lady Gaga</RouterLink></td>
          <td>650</td>
        </tr>
      </tbody>
    </table>
  </article>

  <!-- Spazio vuoto a destra -->
  <aside class="col-3"></aside>
</template>