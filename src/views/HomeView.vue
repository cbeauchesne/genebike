<script setup lang="ts">
</script>

<template>
  <main>
    <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" />

    <div class="greetings">
      <h1 class="green">Génébike</h1>
      <h3>
        Soyez prêts!
      </h3>
    </div>
  </main>
</template>


<style scoped>
.logo {
  display: block;
  margin: 0 auto 2rem;
}

h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {

  .greetings h1,
  .greetings h3 {
    text-align: left;
  }

  .logo {
    margin: 0 2rem 0 0;
  }

}
</style>
