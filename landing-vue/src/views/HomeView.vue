<!-- <script>
import HeroSection from '@/components/HeroSection.vue'
import AboutUsSection from '@/components/AboutUsSection.vue'
import ServicesSection from '@/components/ServicesSection.vue'
import ContactSection from '@/components/ContactSection.vue'

export default {
  name: 'HomeView',
  components: {
    HeroSection,
    AboutUsSection,
    ServicesSection,
    ContactSection
  }
}
</script>








<!-landing-vue/
├── public/
├── src/
│   ├── assets/              # Images, logos, etc.
│   ├── components/          # Blocs réutilisables (Header, Footer, etc.)
│   ├── views/               # Pages complètes (HomeView.vue, AboutView.vue...)
│   ├── router/
│   │   └── index.js         # Définition des routes
│   ├── App.vue              # Composant principal
│   └── main.js              # Point d’entrée de l’app
├── package.json -->





<!-- 
<template>
  <div>
  <div class="home">
    <HeroSection />
  </div>
  <div class="services">
    <ServicesSection/>
  </div>
  <div class="aboutus">
    <AboutUsSection/>
  </div>
  <div class="contact">
    <ContactSection/>
  </div>
</div>
</template>

 -->
 
 <template>
  <div>
    <h2>Page d'accueil BizXO</h2>
    <HeroSection />
  </div>
</template>

<script>
import HeroSection from '@/components/HeroSection.vue'

export default {
  name: 'HomeView',
  components: {
    HeroSection
  }
}
</script>
