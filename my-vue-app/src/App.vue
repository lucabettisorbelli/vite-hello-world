<script>
//Importiamo i componenti da usare
import AppTitle from './components/AppTitle.vue'
import AppContent from './components/AppContent.vue'
//Definiamo l'oggetto che conterrà la lista dei componenti importati, che vogliamo usare
export default {
  components: {
    AppTitle,
    AppContent
  }
}
</script>

<!-- Qui inseriamo l'HTML della nostra App -->
<template>
  <main>
    <!-- Usiamo i componenti importati sopra -->
    <!-- il contenuto è nei relativi file (cartella "components") -->
    <p>
      Check out
      <a href="https://vuejs.org/guide/quick-start.html#local" target="_blank">create-vue</a>, the official Vue + Vite
      starter
    </p>
    <p>
      Install
      <a href="https://github.com/vuejs/language-tools" target="_blank">Volar</a>
      in your IDE for a better DX
    </p>
    <p class="read-the-docs">Click on the Vite and Vue logos to learn more</p>
    <AppContent />
  </main>
</template>

<!-- Qui abbiamo eventuale stile del componente "App", che è il contenitore generale -->
<style scoped>
.read-the-docs {
  color: #888;
}
</style>
