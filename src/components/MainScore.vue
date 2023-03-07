<script setup>
import useScore from '@/composables/useScore'
const { score } = useScore()
</script>

<template>
    <p class="score">Score: {{ score }}</p>
</template>

<style lang="postcss" scoped>
  .score {
  @apply absolute bottom-0 right-3 m-8 text-2xl font-bold uppercase text-white;
}
</style>