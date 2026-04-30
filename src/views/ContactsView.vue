<script setup>
import { RouterLink } from 'vue-router'
</script>

<template>
  <!-- Titolo a larghezza intera come nelle altre pagine -->
  <div class="col-12">
    <h1>Contatti</h1>
  </div>

  <!-- Spazio vuoto a sinistra per centrare i contenuti -->
  <aside class="col-3"></aside>

  <!-- Contenuto principale al centro -->
  <article class="col-6">
    <div>
      <h3>Contatti personali</h3>
      <p>
        Hai bisogno di assistenza, vuoi segnalare un bug o proporre una collaborazione per Cineva? Puoi scrivermi direttamente al mio indirizzo email universitario. Cercherò di risponderti il prima possibile:
        <br><br>
        <b>Email:</b> <a href="mailto:a.casertano@studenti.unica.it">a.casertano@studenti.unica.it</a>
      </p>
    </div>

    <hr>

    <div>
      <h3>Sede legale</h3>
      <p>
        Il progetto Cineva è stato interamente pensato, sviluppato e gestito dalla seguente sede:
        <br><br>
        <b>Quartu Sant'Elena (CA)</b>
      </p>
    </div>
  </article>

  <!-- Spazio vuoto a destra -->
  <aside class="col-3"></aside>
</template>