<template>
    <div class="flex flex-col" role="main">
    
      <div class="relative h-screen bg-cover bg-center" style="background-image: url('https://cdn.builder.io/api/v1/image/assets/TEMP/b3c35aea73a8affad517adfb04580f3643fd42407128221b85acd39150631e70');">
      <!-- Menu -->
      <header class="absolute top-0 w-full z-50">
        <nav class="flex items-center justify-between px-6 py-4">
          
          <!-- Desktop Menu -->
          <ul class="hidden md:flex items-center space-x-8 text-white">
            <li><a href="#" class="hover:text-gray-300">Home</a></li>
            <li><a href="#" class="hover:text-gray-300">Product</a></li>
            <li><a href="#" class="hover:text-gray-300">Pricing</a></li>
            <li><a href="#" class="hover:text-gray-300">About</a></li>
            <li><a href="#" class="hover:text-gray-300">Contact</a></li>
          </ul>
          <!-- Logo -->
          <div class="flex items-center">
            <img src="@/assets/logo.png" alt="Logo" class="h-10 w-auto" />
          </div>
  
          <div class="hidden md:flex items-center space-x-4">
            <a href="#" class="text-white hover:text-gray-300">
              <i class="fab fa-twitter"></i>
            </a>
            <a href="#" class="text-white hover:text-gray-300">
              <i class="fab fa-facebook-f"></i>
            </a>
            <a href="#" class="text-white hover:text-gray-300">
              <i class="fab fa-linkedin-in"></i>
            </a>
          </div>
  
  
          <!-- Hamburger Icon -->
          <button @click="toggleMenu" class="md:hidden text-white focus:outline-none">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7" />
            </svg>
          </button>
        </nav>
  
        <!-- Mobile Menu -->
        <ul
    v-if="isMenuOpen"
    class="md:hidden absolute top-16 left-0 w-full bg-gray-100 text-white space-y-6 py-6 px-6 flex flex-col items-center"
  >
    <li><a href="#" class="block text-xl border-b-2 border-gray-600 py-2">Home</a></li>
    <li><a href="#" class="block text-xl border-b-2 border-gray-600 py-2">Product</a></li>
    <li><a href="#" class="block hover:text-gray-400 text-xl">Pricing</a></li>
    <li><a href="#" class="block hover:text-gray-400 text-xl">About</a></li>
    <li><a href="#" class="block hover:text-gray-400 text-xl">Contact</a></li>
  </ul>
  
  
      </header>
  
      <!-- Contenu principal -->
      <div class="flex flex-col items-center justify-center h-full text-center">
        <h1 class="text-white text-4xl md:text-6xl font-bold leading-tight">
          The best products <br /> start with Figma
        </h1>
        <p class="text-gray-200 text-lg mt-4">
          Most calendars are designed for teams. Slate is designed for freelancers
        </p>
        <button class="mt-6 bg-blue-500 hover:bg-blue-600 text-white font-bold py-3 px-8 rounded-full shadow-lg">
          Try For Free
        </button>
      </div>
    </div>
  
    <main>
     <Features/>
     <LightSection/>

     
     <TestimonialsSection/>
     <PricingSection/>
     <ContactSection/>
     
    </main>

    </div>
  </template>
  
  <script>
  import PricingSection from './pricing-component.vue';
  import Features from './features-component.vue';
  import LightSection from './light-section.vue';
  import ContactSection from './contact-section.vue';
   import TestimonialsSection from './testimonials-section.vue';
  

  export default {
    name: 'LandingPage',
    components: {
        PricingSection, Features, LightSection, ContactSection, TestimonialsSection
    },
    props: {
      msg: String
    },
    data() {
      return {
        isMenuOpen: false, // Contrôle l'état du menu mobile
      };
    },
    methods: {
      toggleMenu() {
        
          this.isMenuOpen = !this.isMenuOpen; 
         console.log('Menu toggled:', this.isMenuOpen);
      },
    },
  }
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped>
  h3 {
    margin: 40px 0 0;
  }
  ul {
    list-style-type: none;
    padding: 0;
  }
  li {
    display: inline-block;
    margin: 0 10px;
  }
  a {
    color: #42b983;
  }
  </style>