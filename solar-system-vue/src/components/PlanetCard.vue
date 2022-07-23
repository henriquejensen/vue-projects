<script setup lang="ts">
defineProps<{ planetName: string; planetImage: string }>();

function renderAltText(planet: string) {
  return `Planeta ${planet}`;
}
</script>

<template>
  <div data-testid="planet-card">
    <p data-testid="planet-name">{{ planetName }}</p>
    <img :src="planetImage" :alt="renderAltText(planetName)" />
  </div>
</template>

<style>
img {
  width: 100%;
}
</style>
