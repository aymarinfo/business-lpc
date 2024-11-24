<template>
    <div class="bg-gray-800 text-white py-16">
  <div class="text-center mb-12">
    <h2 class="text-4xl font-bold">Pricing</h2>
    <p class="mt-4 text-lg">Most calendars are designed for teams. Slate is designed for freelancers</p>
  </div>
  <div class="flex flex-col md:flex-row justify-center items-center gap-8">
    <!-- Free Plan -->
    <div class="bg-white text-gray-800 rounded-lg shadow-lg p-6 w-80">
      <h3 class="text-xl font-bold text-center">FREE</h3>
      <p class="text-center mt-2">Organize across all apps by hand</p>
      <div class="text-center mt-6">
        <span class="text-5xl font-bold">0</span>
        <span class="text-lg">$/Per Month</span>
      </div>
      <ul class="mt-6 space-y-2">
        <li class="text-center">Pricing Feature</li>
        <li class="text-center">Pricing Feature</li>
        <li class="text-center">Pricing Feature</li>
        <li class="text-center">Pricing Feature</li>
        <li class="text-center">Pricing Feature</li>
      </ul>
      <div class="text-center mt-6">
        <button class="py-3 px-8 bg-blue-500 text-white rounded-full hover:bg-blue-600">
          Order Now
        </button>
      </div>
    </div>
    <!-- Standard Plan -->
    <div class="bg-blue-500 text-white rounded-lg shadow-lg p-6 w-80">
      <h3 class="text-xl font-bold text-center">STANDARD</h3>
      <p class="text-center mt-2">Organize across all apps by hand</p>
      <div class="text-center mt-6">
        <span class="text-5xl font-bold">10</span>
        <span class="text-lg">$/Per Month</span>
      </div>
      <ul class="mt-6 space-y-2">
        <li class="text-center">Pricing Feature</li>
        <li class="text-center">Pricing Feature</li>
        <li class="text-center">Pricing Feature</li>
        <li class="text-center">Pricing Feature</li>
        <li class="text-center">Pricing Feature</li>
      </ul>
      <div class="text-center mt-6">
        <button class="py-3 px-8 bg-white text-blue-500 rounded-full hover:bg-gray-100">
          Order Now
        </button>
      </div>
    </div>
    <!-- Business Plan -->
    <div class="bg-white text-gray-800 rounded-lg shadow-lg p-6 w-80">
      <h3 class="text-xl font-bold text-center">BUSINESS</h3>
      <p class="text-center mt-2">Organize across all apps by hand</p>
      <div class="text-center mt-6">
        <span class="text-5xl font-bold">99</span>
        <span class="text-lg">$/Per Month</span>
      </div>
      <ul class="mt-6 space-y-2">
        <li class="text-center">Pricing Feature</li>
        <li class="text-center">Pricing Feature</li>
        <li class="text-center">Pricing Feature</li>
        <li class="text-center">Pricing Feature</li>
        <li class="text-center">Pricing Feature</li>
      </ul>
      <div class="text-center mt-6">
        <button class="py-3 px-8 bg-blue-500 text-white rounded-full hover:bg-blue-600">
          Order Now
        </button>
      </div>
    </div>
  </div>
</div>

</template>
<script>
export default {
  name: 'pricing-component',
}
</script>