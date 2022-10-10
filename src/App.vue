<script setup>
import Navbar from './components/Navbar.vue';
import Home from './components/Home.vue';
import About from './components/About.vue';
import Services from './components/Services.vue';
import Skills from './components/Skills.vue';
import Teams from './components/Teams.vue';
import Contact from './components/Contact.vue';
import Footer from './components/Footer.vue';
</script>

<template>
  <div>
    <div class="bg-[url('../src/assets/photo.jpg')] bg-contain bg-no-repeat">
      <Navbar class="sticky top-0"/>
      <Home />
    <About />
    <Services />
    <Skills />
    <Teams />
    <Contact />
    <Footer />
  </div>
    
  </div>
</template>

