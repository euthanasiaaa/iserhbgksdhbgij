<script setup>
import HelloWorld from './components/HelloWorld.vue'

</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="./assets/zaika.svg" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="Уииииииииииии" />
    </div>
  </header>

  <main>
    <img src="./assets/mbl.jpg" alt="" width="500" />
    <img src="./assets/pewpew.jpg" alt="" width="500" />
    <img src="./assets/rrrrrrrrrr.jpg" alt="" width="500" />
    <img src="./assets/sun.jpg" alt="" width="500" />
  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
