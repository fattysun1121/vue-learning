<template>
  <div class="container">
    <div class="left-col">
      <h1>Discover And Collect Rare NFTs</h1>
      <p class="short-p">The most secure marketplace for buying and selling unique crypto assets.</p>
      <div class="buttons">
        <Button class="button" id="buy-button">BUY NFTS</Button>
        <Button class="button" id="sell-button">SELL NFTS</Button>
      </div>
    </div>
    <div class="right-col">
      <img src="../assets/figma/hero.png" alt="Hero page image">
    </div>
  </div>
</template>

<script setup lang="ts">
import { Button } from '@/components/ui/button'
</script>

<style scoped>

#buy-button {
  background-color: #8080D7;
}

#sell-button {
  border-color: #88D0D1;
  border-width: 0.08rem;
}

.container {
  position: relative;
  display: flex;
  justify-content: space-between;
  align-content: start;
}

.left-col {
  display: flex;
  flex-direction: column;
  gap: 2rem;
}

.right-col {
  display: flex;
  flex-direction: column;
  width: 30rem;
  height: auto;
}

.buttons {
  display: flex;
  justify-content: space-between;
}

img {
  width: 100%;
  height: 100%;
}

h1 {
  font-size: 4.375rem;
  font-weight: bold;
  line-height: 4rem;
  width: 25rem;
}

</style>