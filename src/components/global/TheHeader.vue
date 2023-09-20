<template>
  <header id="start" class="bg-gray-900 text-gray-200 shadow-lg select-none">
    <div class="container mx-auto">
      <div class="w-full flex justify-between py-8 px-2">
        <RouterLink to="/">
          <div class="flex">
            <img src="@/assets/imageedit_10_2356505410.png" alt="" width="32" height="32">
            <h2 class="pl-2 block text-2xl font-medium my-auto">Radiant_ldn</h2>
          </div>
        </RouterLink>
        <div class="my-auto">
          <a href="https://www.instagram.com/radiant_ldn" target="_blank">
            <img class="grayscale hover:grayscale-0 opacity-70 hover:opacity-100 duration-300" src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/instagram.svg" width="32" height="32" />
          </a>
        </div>
      </div>
    </div>
  </header>
</template>

<script setup>
import { RouterLink } from 'vue-router'
</script>