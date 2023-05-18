<script>
//Definiamo il nome del componente ed eventualmente i componenti che usa (nessuno)
export default {
  name: "AppContent"
}
</script>

<!-- Quando si importa questo componente verrà visualizzato questo HTML al suo posto -->
<template>
  <div>
    <h2>Ciao mondo!</h2>
    <div>
      <h2>Vue</h2>
      <img alt="Vue logo" class="logo" src="../assets/vue.svg" width="125" height="125" />
    </div>
    <div>
      <h2>Vite</h2>
      <img alt="Vue logo" class="logo" src="/vite.svg" width="125" height="125" />
    </div>
  </div>
</template>

<!-- Non c'è stile speicifoc per il componente, usiamo solo quanto c'è in  style.css -->