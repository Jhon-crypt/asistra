<script setup>
import Header from './components/Header/Header.vue';
import HeaderHero from './components/Hero/HeaderHero.vue'
import FeatureHero from './components/Hero/FeatureHero.vue'
import ServicesSection from './components/section/ServicesSection.vue'
import ProjectSection from './components/section/ProjectSection.vue'
import ContactSection from './components/section/ContactSection.vue'
import Footer from './components/footer/Footer.vue'
</script>

<template>
  <div>

    <section class="relative pb-10 bg-coolGray-50 overflow-hidden">

      <Header />

      <HeaderHero />

      <FeatureHero />

      <ServicesSection />

      <ProjectSection />

      <ContactSection />

      <Footer />

    </section>
    
  </div>
</template>

