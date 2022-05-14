<script setup>
import AccountOutlineIcon from 'vue-material-design-icons/AccountOutline.vue';
import MagnifyIcon from 'vue-material-design-icons/Magnify.vue'
</script>
<template>
  <div class="lg:z-20 lg:fixed w-full flex flex-col items-center">
    <div class="w-full py-8 lg:pt-8 lg:pb-12 px-12 flex items-center justify-between lg:bg-cyan-700 lg:-mb-[60px] lg:shadow-md">
      <div class="flex flex-col items-center">
        <h2 class="font-bold text-cyan-700 lg:text-gray-100 text-2xl -mb-2">DO</h2>
        <h2 class="font-bold text-cyan-700 lg:text-gray-100 text-2xl">CS</h2>
      </div>
      <div class="hidden px-12 lg:flex flex-grow">
        <h1 class="font-semibold text-gray-100 text-2xl">Let's find you a doctor</h1>  
      </div>
      <div class="bg-gray-100 rounded-2xl py-2 px-2">
        <AccountOutlineIcon fillColor="#999" size="28"/>
      </div>    
    </div>
    <div class="w-full px-12 flex items-center justify-start lg:hidden">
      <h1 class="font-semibold text-xl">Let's find you a doctor</h1>
    </div>
    <div class="w-full z-10 lg:w-3/4 py-8 px-12 flex items-center justify-between lg:space-x-8">
      <div class="lg:shadow-md w-full py-3 px-4 rounded-xl flex items-center justify-between bg-gray-100">
        <input class="flex-grow bg-gray-100 text-xl outline-none h-full" type="text" placeholder="Search">
        <MagnifyIcon class="w-8" fillColor="#999" size="32"/>
      </div>
      <div class="hidden lg:flex">
        <select name="" id="" class="lg:shadow-md py-3 px-4 rounded-xl bg-gray-100 text-xl outline-none h-full text-gray-400">
          <option value="" selected>location</option>
        </select>
      </div>
    </div>
  </div>
</template>
<style scoped>
</style>
