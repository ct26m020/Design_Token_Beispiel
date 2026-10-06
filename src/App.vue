<script setup lang="ts">
import GoodCard from './components/GoodCard.vue'
import BadCard from './components/BadCard.vue'
</script>

<template>
  <main class="cards">
    <GoodCard />
    <BadCard />
  </main>
</template>

<style scoped>
.cards {
  display: flex;
  gap: var(--space-l);
  flex-wrap: wrap;
}
</style>
