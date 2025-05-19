<template>
  <div class="bg-zinc-700 min-h-screen">
    <Navbar />
    <div class="main container mx-auto px-4 py-6">
      <router-view/>
    </div>
    <Footer />
  </div>
</template>

<script setup>
import Navbar from './components/NavbarComponent.vue'
import Footer from './components/FooterComponent.vue'
</script>