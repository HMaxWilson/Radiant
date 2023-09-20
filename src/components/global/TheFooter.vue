<template>
  <footer class="bg-black border-t border-gray-500 text-gray-400 select-none">
    <div class="container mx-auto py-2 px-2">
      <div class="flex flex-wrap items-center justify-between">
        <div class="flex text-sm">
          <a href="#start">^ Back to top</a>
        </div>
        <div class="flex text-sm space-x-4">
          <a href="https://www.instagram.com/radiant_ldn" target="_blank">
            <img class="grayscale hover:grayscale-0 opacity-70 hover:opacity-100 duration-300" src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/instagram.svg" width="32" height="32" />
          </a>
        </div>
      </div>
      <div class="text-center py-2">
        &copy; Radiant_ldn<a class="opacity-60 hover:opacity-100" href="https://www.astronomad.co.uk/" target="_blank"> | AstroNomad x Design</a>
      </div>
    </div>
  </footer>
</template>

<script setup>
import { RouterLink } from 'vue-router'
</script>