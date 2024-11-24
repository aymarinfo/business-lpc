<template>
    <div class="container mx-auto px-4 py-8">
     
      <div class="flex flex-col md:flex-row gap-8">
        
        
        <div class="flex-1">
          <h2 class="text-3xl font-bold text-gray-800 mb-4">
            Fastest way to organize
          </h2>
          <p class="text-lg text-gray-600 mb-6">
           Most calendars are designed for teams. Slate is designed for freelancers
          </p>
          <button
            class="bg-blue-500 text-white py-2 px-6 rounded-full hover:bg-blue-600 transition duration-300"
          >
            Try For Free
          </button>
        </div>   
        <div class="flex-1">
          <img src="@/assets/images/laptop.png" alt="Produit" class="w-full h-auto rounded-lg shadow-lg"/>
        </div>
      </div>

      <div class="flex flex-col md:flex-row gap-8 p-5">
        
        <div class="flex-1">
          <img src="@/assets/images/undraw_newsletter_vovu.png" alt="Produit" class="w-full h-auto rounded-lg shadow-lg"/>
        </div>

        <div class="flex-1 pt-10">
            <h1 class="text-1xl font-bold text-gray-800 mb-4">
            Lightning fast prototyping
          </h1>
          <h2 class="text-1xl font-bold text-gray-800 mb-4">
            Subscribe to our Newsletter
          </h2>
          <p class="text-lg text-gray-600 mb-6">
            Available exclusivery on Figmaland
          </p>

          <div class="flex">
            <div>
            <input type="text" id="name" placeholder="Your email" class="py-2 px-6  mr-5 mt-1 w-full border-gray-300 rounded-lg shadow-sm focus:ring-blue-500 focus:border-blue-500">
          </div>
          <button
            class="bg-blue-500 text-white py-2 px-6 rounded-full hover:bg-blue-600 transition duration-300"
          >
            Subscribe
          </button>
          </div>
          
        </div>   

      </div>

    </div>

    
  </template>

<script>
        export default {
        name: 'light-section',
      }
     
</script>