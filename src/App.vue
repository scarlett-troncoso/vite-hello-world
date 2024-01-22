<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header class="bg-light"> Header
    <div>
      <h1>
        HELLO WORLD ☺ ☺ ☺
      </h1>
    </div>
  </header>

  <main>Main</main>

  <footer>Footer</footer>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}

.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}

.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
