<script lang="ts">
  const images = [
    {
      src: "/generated/image-advanced-life-support-ambulance-interior-1765725879303-1.webp",
      title: "Advanced Life Support Ambulance",
      desc: "AIS-125 Certified"
    },
    {
      src: "/generated/image-red-fire-truck-rapid-response-vehicle-mo-1765725881757-2.webp",
      title: "Rapid Response Vehicle",
      desc: "Firefighting Equipment"
    },
    {
      src: "/generated/image-fleet-of-white-ambulances-lined-up-gover-1765725884248-3.webp",
      title: "Government Fleet Solutions",
      desc: "Bulk Order Capability"
    }
  ];
</script>

<section class="bg-white pb-24 overflow-hidden">
  <div class="flex gap-4 overflow-x-auto px-6 pb-8 snap-x">
    {#each images as img}
      <div class="min-w-[80vw] md:min-w-[60vw] lg:min-w-[45vw] h-[400px] snap-center first:pl-0">
        <img src={img.src} alt={img.title} class="w-full h-full object-cover rounded-lg" />
      </div>
    {/each}
  </div>
  
  <div class="text-center mt-4">
    <p class="text-gray-500 text-sm mb-4">Specialized Emergency Vehicles <span class="text-gray-400">1000+ Projects Completed</span></p>
    <div class="flex justify-center gap-2">
      <div class="w-1.5 h-1.5 rounded-full bg-gray-800"></div>
      <div class="w-1.5 h-1.5 rounded-full bg-gray-300"></div>
      <div class="w-1.5 h-1.5 rounded-full bg-gray-300"></div>
    </div>
  </div>
</section>
