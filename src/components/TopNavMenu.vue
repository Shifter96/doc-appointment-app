<script setup>
  import AccountOutlineIcon from 'vue-material-design-icons/AccountOutline.vue';
  import ArrowLeftIcon from 'vue-material-design-icons/ArrowLeft.vue'
</script>
<template>
  <div class="w-full py-8 px-12 flex items-center justify-between lg:bg-cyan-700">
    <div class="rounded-2xl py-2 px-2 cursor-pointer">
      <ArrowLeftIcon fillColor="#ccc" size="28"/>
    </div>
    <div class="bg-gray-100 rounded-2xl py-2 px-2 cursor-pointer">
      <AccountOutlineIcon fillColor="#999" size="28"/>
    </div>    
  </div>
</template>
<style scoped>
</style>