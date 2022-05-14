<script setup>
  import MapMarkerIcon from 'vue-material-design-icons/MapMarker.vue'
  import StarIcon from 'vue-material-design-icons/Star.vue'

  defineProps({
    
  });
</script>

<template>
  <div class="w-full px-8 py-6 flex items-center border-b-[2px] border-gray-300 lg:border-none lg:max-w-[400px] lg:mx-4 lg:my-2 lg:bg-gray-100 lg:rounded-xl lg:px-4 lg:py-3 cursor-pointer">
    <div class="h-24 w-24 rounded-md overflow-hidden">
      <img class="object-cover h-full" src="../assets/doctor.jpg" alt="doctor_image">
    </div>
    <div class="px-4 flex-grow flex flex-col items-start">
      <h2 class="font-semibold text-cyan-700">Dr.Amine Mohammed</h2>
      <h3 class="font-medium text-sm text-gray-500">Spécialité : Chirurgie dentaire</h3>
      <h3 class="font-light text-gray-500">CHU Mustapha</h3>
      <div class="w-full flex items-center justify-between">
        <div class="flex items-center text-gray-500">
          <MapMarkerIcon size="18"/><span>Alger</span>
        </div>
        <div class="flex items-center">
          <StarIcon fillColor="orange" size="18"/>
          <StarIcon fillColor="orange" size="18"/>
          <StarIcon fillColor="orange" size="18"/>
          <StarIcon fillColor="orange" size="18"/>
          <StarIcon size="18"/>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
</style>