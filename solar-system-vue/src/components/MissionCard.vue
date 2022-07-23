<script setup lang="ts">
defineProps<{
  name: string;
  year: string;
  country: string;
  destination: string;
}>();
</script>

<template>
  <div data-testid="mission-card">
    <p data-testid="mission-name">{{ name }}</p>
    <p data-testid="mission-year">{{ year }}</p>
    <p data-testid="mission-country">{{ country }}</p>
    <p data-testid="mission-destination">{{ destination }}</p>
  </div>
</template>
