<template>
  <main>
    <NavBar />
    <Hero />
  </main>
</template>

<script setup lang="ts">
import NavBar from './components/NavBar.vue'
import Hero from './components/Hero.vue'
</script>

<style>

 /* Global Styling */
body {
  background-color: #010922;
  color: white;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Outfit';
}

a {
  color: white;
  text-decoration: none;
}

p {
  color: inherit;
  font-family: Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  font-size: 1.125rem;
}

main {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  right: 0;
  margin: 0rem 11rem;
  display: flex;
  flex-direction: column;
  gap: 8rem;
}

.button {
  padding: 0.4rem 3.2rem;
  border-radius: 3.2rem;
}

.short-p {
  width: 25rem;
}
</style>
