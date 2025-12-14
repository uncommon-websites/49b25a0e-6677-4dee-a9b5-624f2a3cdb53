<script lang="ts">
  let selectedColor = 'white';
</script>

<section class="bg-[#f9f9f7] py-24 px-6" id="products">
  <div class="max-w-[1200px] mx-auto text-center">
    <h2 class="text-[40px] font-light text-gray-900 mb-16">
      Multiple vehicle types. <span class="text-gray-400">Customized to your needs.</span>
    </h2>

    <div class="mb-8">
      <h3 class="text-2xl font-normal mb-2">AIS-125 Certified Ambulance</h3>
      <p class="text-gray-500 text-sm">Advanced Life Support • Basic Life Support • Patient Transport</p>
    </div>

    <!-- Vehicle Image -->
    <div class="relative w-full h-[400px] bg-white rounded-xl mb-8 flex items-center justify-center overflow-hidden shadow-sm">
      <div class="absolute inset-0 flex items-center justify-between px-4">
        <button class="w-10 h-10 rounded-full bg-gray-100 flex items-center justify-center hover:bg-gray-200">
          <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m15 18-6-6 6-6"/></svg>
        </button>
        <button class="w-10 h-10 rounded-full bg-gray-100 flex items-center justify-center hover:bg-gray-200">
          <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m9 18 6-6-6-6"/></svg>
        </button>
      </div>
      <img src="/generated/image-modern-white-ambulance-with-red-stripe-a-1765725876089-0.webp" class="h-[80%] object-contain" alt="AIS-125 Ambulance" />
    </div>

    <!-- Vehicle Types -->
    <div class="flex justify-center gap-4 mb-8">
      <button class="px-4 py-2 rounded-full bg-primary-100 border-2 border-primary-500 text-primary-900 text-xs font-medium">Ambulance</button>
      <button class="px-4 py-2 rounded-full bg-gray-100 text-gray-600 text-xs font-medium hover:bg-gray-200">Fire Truck</button>
      <button class="px-4 py-2 rounded-full bg-gray-100 text-gray-600 text-xs font-medium hover:bg-gray-200">Mobile Clinic</button>
      <button class="px-4 py-2 rounded-full bg-gray-100 text-gray-600 text-xs font-medium hover:bg-gray-200">Custom Build</button>
    </div>

    <div class="flex justify-center gap-8 text-sm text-gray-600 mb-4 border-b border-gray-200 pb-4 inline-flex mx-auto w-auto px-12">
      <span>AIS-125 Certified</span>
      <span>FRP Body</span>
      <span>Medical Equipment</span>
    </div>

    <p class="text-xs text-gray-500 mb-8">
      Trusted by <span class="font-bold text-gray-900">20+ Government Departments</span> and healthcare institutions.<br>
      Bulk orders and urgent requirements handled efficiently.
    </p>

    <div class="flex justify-center gap-4">
      <button class="px-6 py-3 bg-gray-100 hover:bg-gray-200 rounded-lg text-sm font-medium transition-colors text-left">
        <span class="block text-[10px] text-gray-500">Want to see more?</span>
        <span class="text-primary-600">View all vehicle models</span>
      </button>
      <button class="px-6 py-3 bg-primary-600 hover:bg-primary-700 text-white rounded-lg text-sm font-medium transition-colors flex items-center gap-2">
        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/><polyline points="7 10 12 15 17 10"/><line x1="12" y1="15" x2="12" y2="3"/></svg>
        Download Brochure
      </button>
    </div>
  </div>
</section>
