<script setup>
import Navbar from './components/Navbar.vue';
import Home from './components/Home.vue';
import About from './components/About.vue';
import Services from './components/Services.vue';
</script>

<template>
  <div>
    <div class="bg-[url('../src/assets/photo.jpg')] bg-contain bg-no-repeat">
      <Navbar class="sticky top-0"/>
      <Home />
    <About />
    <Services />
  </div>
    
  </div>
</template>

