<script setup>
  import MapMarkerIcon from 'vue-material-design-icons/MapMarker.vue'
  import TopNavMenu1 from '../components/TopNavMenu.vue';
  import StarIcon from 'vue-material-design-icons/Star.vue'
</script>
<template>
  <TopNavMenu1/>
  <div class="w-full py-8 px-12 flex flex-col items-center">
    <div class="z-10 h-40 w-40 rounded-xl overflow-hidden shadow-md">
      <img class="w-full h-full object-cover" src="../assets/doctor.jpg" alt="doctor_image">
    </div>
    <div class="-mt-20 pt-28 pb-8 px-8 w-full rounded-xl border-[1px] border-gray-100 bg-[#f9fafb] flex flex-col items-center">
      <h2 class="font-semibold text-xl text-cyan-700">Dr. Amine Mohammed</h2>
      <h2 class="mt-4 font-medium text-xl text-gray-500">Spécialité : Chirurgie dentaire</h2>
      <h3 class="mt-4 font-light text-xl text-gray-500">CHU Mustapha</h3>
      <div class="flex items-center text-gray-500">
        <MapMarkerIcon size="18"/><span>Alger</span>
      </div>
      <div class="mt-4 w-full flex items-center justify-between space-x-8">
        <div class="flex flex-col items-center">
          <h3 class="font-light text-lg text-gray-500">Rating</h3>
          <h1 class="text-5xl text-gray-500">4.3</h1>
          <div class="mt-2 flex flex-col">
            <div class="flex items-center">
              <StarIcon fillColor="orange" size="12"/>
              <StarIcon fillColor="orange" size="12"/>
              <StarIcon fillColor="orange" size="12"/>
              <StarIcon fillColor="orange" size="12"/>
              <StarIcon size="12"/>
            </div>
            <p class="text-gray-500 text-xs">40.000</p>
          </div>
        </div>
        <div class="w-full flex flex-col">
          <div class="flex items-center justify-between space-x-2">
            <span class="font-medium text-cyan-700">5</span>
            <div class="w-full bg-gray-300 rounded-full h-1.5">
              <div class="bg-cyan-700 h-1.5 rounded-full" style="width: 45%"></div>
            </div>
          </div>
          <div class="flex items-center justify-between space-x-2">
            <span class="font-medium text-cyan-700">5</span>
            <div class="w-full bg-gray-300 rounded-full h-1.5">
              <div class="bg-cyan-700 h-1.5 rounded-full" style="width: 45%"></div>
            </div>
          </div>
          <div class="flex items-center justify-between space-x-2">
            <span class="font-medium text-cyan-700">5</span>
            <div class="w-full bg-gray-300 rounded-full h-1.5">
              <div class="bg-cyan-700 h-1.5 rounded-full" style="width: 45%"></div>
            </div>
          </div>
          <div class="flex items-center justify-between space-x-2">
            <span class="font-medium text-cyan-700">5</span>
            <div class="w-full bg-gray-300 rounded-full h-1.5">
              <div class="bg-cyan-700 h-1.5 rounded-full" style="width: 45%"></div>
            </div>
          </div>
          <div class="flex items-center justify-between space-x-2">
            <span class="font-medium text-cyan-700">5</span>
            <div class="w-full bg-gray-300 rounded-full h-1.5">
              <div class="bg-cyan-700 h-1.5 rounded-full" style="width: 45%"></div>
            </div>
          </div>  
        </div>
      </div>
    </div>
    <button class="mt-8 w-full py-3 rounded-xl text-center font-medium text-xl bg-cyan-700 text-white">Prendre rendez-vous</button>
  </div>
</template>
<style scoped>
</style>