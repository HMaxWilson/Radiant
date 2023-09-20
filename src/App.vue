<script setup>
import { RouterView } from 'vue-router'
import Header from './components/global/TheHeader.vue'
import Footer from './components/global/TheFooter.vue'
</script>

<template>
  <Header />

  <main class="container mx-auto py-4">
    <RouterView />
  </main>

  <Footer />
</template>
