<script setup lang="ts">
import Title from "./Title.vue";
import missions from "../data/missions";
import MissionCard from "./MissionCard.vue";
</script>

<template>
  <div data-testid="missions">
    <Title headline="Missões" />
    <div v-for="mission in missions">
      <MissionCard
        :name="mission.name"
        :country="mission.country"
        :destination="mission.destination"
        :year="mission.year"
      />
    </div>
  </div>
</template>
