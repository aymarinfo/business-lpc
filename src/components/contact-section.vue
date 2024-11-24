
<template>
<div class="container mx-auto px-4 py-8">
    <div class="text-center mb-8">
      <h1 class="text-2xl font-semibold text-gray-800">Contact Us  ee</h1>
      <p class="text-gray-600">Most calendars are designed for teams. <br> Slate is designed for freelancers</p>
    </div>
    <div class="flex flex-wrap justify-center gap-8">
      <!-- Form Section -->
      <div class="bg-white shadow-md rounded-lg p-6 w-full md:w-96">
        <form class="space-y-4">
          <div>
            
            <input type="text" id="name" placeholder="Your Name" class="py-2 px-6 mt-1 w-full border-gray-300 rounded-lg shadow-sm focus:ring-blue-500 focus:border-blue-500">
          </div>
          <div>
            
            <input type="email" id="email" placeholder="Your Email" class="py-2 px-6 mt-1 w-full border-gray-300 rounded-lg shadow-sm focus:ring-blue-500 focus:border-blue-500">
          </div>
          <div>
        
            <textarea id="message" placeholder="Your Message" class="mt-1 w-full border-gray-300 rounded-lg shadow-sm focus:ring-blue-500 focus:border-blue-500"></textarea>
          </div>
          <button type="submit" class="w-full bg-blue-500 text-white py-2 rounded-lg hover:bg-blue-600 transition">Send</button>
        </form>
      </div>

      
      <div class="w-full md:w-96 text-center">
        <div class="flex flex-wrap justify-center gap-8 items-center text-gray-700">
            <div class="flex items-center space-x-2">
                <i class="fas fa-map-marker-alt text-blue-500"></i>
                <p class="text-sm">6386 Spring St, Anchorage, Georgia 12473, United States</p>
            </div>
            <div class="flex items-center space-x-2">
                <i class="fas fa-phone-alt text-blue-500"></i>
                <p class="text-sm">(843) 555-0130</p>
            </div>
            <div class="flex items-center space-x-2">
                <i class="fas fa-envelope text-blue-500"></i>
                <p class="text-sm">willie.jennings@example.com</p>
            </div>
        </div>



        <div class="h-60">
          <iframe
            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3153.021101332!"
            class="rounded-lg w-full h-full border-0"
            loading="lazy"
          ></iframe>
        </div>
        <!-- Social Media Icons -->
        <div class="flex justify-center mt-4 space-x-4 text-blue-500">
          <a href="#" class="hover:text-blue-600"><i class="fab fa-twitter"></i></a>
          <a href="#" class="hover:text-blue-600"><i class="fab fa-facebook"></i></a>
          <a href="#" class="hover:text-blue-600"><i class="fab fa-linkedin"></i></a>
        </div>
      </div>
    </div>
  </div>
   </template>

<script>
        export default {
        name: 'contact-section',
      }
     
</script>