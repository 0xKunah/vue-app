<script setup>
import { RouterLink } from 'vue-router'
</script>

<template>
  <div id="topbar" class='overflow-auto z-30 absolute top-0 w-full h-12 flex font-semibold text-gray-700 items-center px-4 bg-gradient-to-r from-blue-600 via-blue-500 to-blue-400'>
    <RouterLink to="/" class='ml-2 text-gray-200'>Home</RouterLink>

    <div class="flex-grow"></div>
    <RouterLink to="/hellow">Contact</RouterLink>
  </div>
</template>