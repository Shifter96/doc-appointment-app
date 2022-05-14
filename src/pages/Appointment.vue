<script setup>
  import TopNavMenu from '../components/TopNavMenu.vue';
  import Card from '../components/Card.vue';
</script>
<template>
  <TopNavMenu/>
  <div class="w-full py-2 px-12 flex items-center">
    <h1 class="font-semibold text-gray-900 text-3xl">Take an appointment with</h1>
  </div>
  <Card/>
  <div class="w-full py-8 px-12 flex items-center">
    <button class="w-full py-3 rounded-xl text-center font-medium text-xl bg-cyan-700 text-white">Confirmer</button>
  </div>
  <v-date-picker v-model="date" />
</template>
<style scoped>
</style>