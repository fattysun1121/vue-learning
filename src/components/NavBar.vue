<template>
  <div class="container">
    <span class="title">KRYPTO</span>
    <ul>
      <li><a href="">about</a></li>
      <li><a href="">pricing</a></li>
      <li><a href="">contact</a></li>
      <li><a href="">buy nfts</a></li>
    </ul>
  </div>
</template>

<script setup lang="ts">

</script>

<style scoped>
.container {
  position: relative;
  display: flex;
  justify-content: space-between;
}

.title {
  font-weight: bold;
  font-size: 1.25rem;
}

ul {
  list-style-type: none;
  padding: 0; 
  display: flex;
  gap: 6rem;
}

.title, ul {
  margin: 1.1rem 0rem;
}  

a:hover {
  background-color: inherit;
}

a::after {
  display: block;
  content: "";
  height: 0.1rem;
  width: 0%;
  background-color: #fff;
  transition: width 0.1s linear;
  margin: 0 auto;
}

a:hover::after {
  width: 100%;
}


</style>