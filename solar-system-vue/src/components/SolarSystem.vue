<script setup lang="ts">
import Title from "./Title.vue";
import PlanetCard from "./PlanetCard.vue";
import planets from "../data/planets";
</script>

<template>
  <div data-testid="solar-system">
    <Title headline="Planetas" />
    <div v-for="planet in planets">
      <PlanetCard :planet-name="planet.name" :planet-image="planet.image" />
    </div>
  </div>
</template>
