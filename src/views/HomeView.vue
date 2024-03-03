<script setup lang="ts">
</script>

<template>
  <main>
    <img alt="Vue logo" class="logo" src="@/assets/genepi.png" width="200" />
    <h1 class="title is-1">Génébike 2024</h1>
    <h3 class="subtitle is-3">Soyez prêts!</h3>
  </main>
</template>


<style scoped>

@keyframes fadeIn1 {
  0% { opacity: 0; }
  33% { opacity: 1; }
  100% { opacity: 1; }
}

@keyframes fadeIn2 {
  0% { opacity: 0; }
  20% { opacity: 0; }
  66% { opacity: 1; }
  100% { opacity: 1; }
}

@keyframes fadeIn3 {
  0% { opacity: 0; }
  40% { opacity: 0; }
  100% { opacity: 1; }
}

main {
  display: flex;
  flex-direction: column;
  place-items: center;
  height: 100vh;
  padding-top: 20vh;
}

img {
  animation: fadeIn1 6s;
}

h1 {
  animation: fadeIn2 6s;
}

h3 {
  animation: fadeIn3 6s;
}

@media screen and (max-width: 340px){
  h1 {
    font-size: 2.5rem!important;
  }
}

</style>
