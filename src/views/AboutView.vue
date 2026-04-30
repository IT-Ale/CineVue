<script setup>
import { RouterLink } from 'vue-router'
</script>

<template>
  <div class="col-12">
    <h1>Cosa è Cineva?</h1>
  </div>

  <aside class="col-3">
    <p id="titoloIndice">Indice</p>
    <ul id="indice">
      <li><a href="#info">Informazioni sul sito</a></li>
      <li><a href="#target">A chi è rivolto il sito?</a></li>
      <li><a href="#cost">Quanto costa?</a></li>
    </ul>
  </aside>

  <article class="col-6">
    <div>
      <h3 id="info">Informazioni sul sito</h3>
      <p>
        Cineva permette a tutti i cinofili di esprimere le proprie opinioni su film e serie tv, creando uno spazio di confronto aperto e stimolante. 
        <br><br>
        Meglio la CGI di <b>Black Widow</b> o quella di <b>Antman: Quantumania</b>? Vi siete già ripresi dall'ultimo, clamoroso episodio di <u>Severance</u>? 
        Oltre a recensire i titoli del momento, su Cineva puoi tenere traccia di tutto ciò che guardi, valutare le performance dei tuoi attori preferiti, creare liste personalizzate per le tue maratone e scoprire capolavori nascosti consigliati da utenti con i tuoi stessi gusti. Che tu sia un fan dei blockbuster d'azione o del cinema d'autore indipendente, qui troverai sempre spunti interessanti e discussioni accese.
      </p>
      <a href="#indice">Torna su</a>
    </div>

    <hr>

    <div>
      <h3 id="target">A chi è rivolto il sito?</h3>
      <p>
        Cineva è rivolto a tutti gli appassionati della settima arte e del binge-watching che vogliono condividere le proprie emozioni con una community attiva e accogliente. 
        <br><br>
        È il rifugio perfetto sia per il critico severo che ama analizzare ogni singola inquadratura e buco di trama, sia per lo spettatore occasionale che cerca semplicemente un buon consiglio per la serata "pizza e divano". Se ami discutere per ore dei finali aperti, se ti piace confrontare i libri con le loro trasposizioni cinematografiche o se vuoi solo tenere un diario visivo di ciò che hai visto durante l'anno, sei decisamente nel posto giusto.
      </p>
      <a href="#indice">Torna su</a>
    </div>

    <hr>

    <div>
      <h3 id="cost">Quanto costa?</h3>
      <p>
        Cineva è completamente gratuito e lo sarà per sempre. 
        <br><br>
        Crediamo fermamente che la cultura cinematografica, la passione per le belle storie e il divertimento della condivisione debbano essere accessibili a tutti senza alcuna barriera. Non troverai funzionalità premium nascoste, paywall per leggere i commenti o abbonamenti mensili da pagare: creando un account avrai accesso immediato e illimitato a tutte le classifiche, alle recensioni complete e agli strumenti di interazione. Il nostro unico "guadagno" è far crescere una community sempre più grande e unita dallo stesso immenso amore per lo schermo.
      </p>
      <a href="#indice">Torna su</a>
    </div>
  </article>

  <aside class="col-3 ads">
    <!-- Spazio per eventuali banner o riempimento -->
  </aside>
</template>