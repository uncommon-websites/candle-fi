<script>
  // GetItAll component
</script>

<section class="py-20 px-4 w-full max-w-7xl mx-auto">
  <div class="flex flex-col lg:flex-row items-center gap-12 lg:gap-20">
    <!-- Left Content -->
    <div class="flex-1 max-w-lg">
      <span class="text-[#FF5A4F] font-medium mb-4 block">Read</span>
      <h2 class="text-4xl md:text-5xl font-bold text-gray-900 mb-4">Get It All</h2>
      <p class="text-gray-500 text-lg mb-8">Unified data. Lightning fast.</p>

      <ul class="space-y-4 mb-10">
        {#each ['Beautiful service link UI', 'Real-time balances & activity', 'Full history since account opening'] as item}
          <li class="flex items-center gap-3">
            <div class="w-5 h-5 rounded-full bg-[#FFF0EF] flex items-center justify-center shrink-0">
              <svg width="10" height="8" viewBox="0 0 10 8" fill="none">
                <path d="M1 4L3.5 6.5L9 1" stroke="#FF5A4F" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
              </svg>
            </div>
            <span class="text-gray-700 font-medium">{item}</span>
          </li>
        {/each}
      </ul>

      <div class="flex items-center gap-4">
        <button class="bg-black text-white px-6 py-3 rounded-full font-medium hover:bg-gray-800 transition-colors">
          Get Started
        </button>
        <button class="bg-white border border-gray-200 text-gray-900 px-6 py-3 rounded-full font-medium hover:bg-gray-50 transition-colors flex items-center gap-2">
          Documentation
          <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
            <path d="M5 12h14M12 5l7 7-7 7" stroke-linecap="round" stroke-linejoin="round"/>
          </svg>
        </button>
      </div>
    </div>

    <!-- Right Illustration -->
    <div class="flex-1 w-full bg-[#F7F7F8] rounded-[2rem] h-[450px] relative overflow-hidden">
      <!-- SVG Lines -->
      <svg class="absolute inset-0 w-full h-full pointer-events-none" viewBox="0 0 600 450" preserveAspectRatio="none">
          <!-- Lines from Center (270, 225) to Right Icons (540, y) -->
          <!-- Top Icon (Venmo) at (540, 90) -->
          <path d="M270 225 C 370 225, 440 90, 540 90" stroke="#FF5A4F" stroke-width="2" stroke-dasharray="6 6" fill="none" opacity="0.4"/>
          <!-- Second Icon (Uber) at (540, 180) -->
          <path d="M270 225 C 370 225, 440 180, 540 180" stroke="#FF5A4F" stroke-width="2" stroke-dasharray="6 6" fill="none" opacity="0.4"/>
          <!-- Third Icon (Airbnb) at (540, 270) -->
          <path d="M270 225 C 370 225, 440 270, 540 270" stroke="#FF5A4F" stroke-width="2" stroke-dasharray="6 6" fill="none" opacity="0.4"/>
          <!-- Bottom Icon (Target) at (540, 360) -->
          <path d="M270 225 C 370 225, 440 360, 540 360" stroke="#FF5A4F" stroke-width="2" stroke-dasharray="6 6" fill="none" opacity="0.4"/>
      </svg>

      <!-- Central Node Group -->
      <div class="absolute top-1/2 left-[35%] -translate-x-1/2 -translate-y-1/2 flex items-center gap-4 z-10">
        <div class="w-16 h-16 bg-white rounded-2xl shadow-sm border border-gray-100 flex items-center justify-center">
            <svg width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="black" stroke-width="1.5">
                <path d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5"/>
            </svg>
        </div>
        <div class="h-[2px] w-12 bg-gray-300 border-t border-b border-dashed border-gray-400"></div>
        <div class="w-16 h-16 bg-gradient-to-br from-purple-400 to-pink-400 rounded-2xl shadow-lg flex items-center justify-center text-white font-bold text-xl">
          SDK
        </div>
      </div>

      <!-- Right Icons -->
      <div class="absolute top-[20%] right-[10%] -translate-y-1/2 w-14 h-14 bg-[#008CFF] rounded-2xl flex items-center justify-center text-white shadow-sm z-10">
          <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"><path d="M18 4L12 20L6 4"/></svg>
      </div>
      
      <div class="absolute top-[40%] right-[10%] -translate-y-1/2 w-14 h-14 bg-black rounded-2xl flex items-center justify-center text-white shadow-sm z-10">
          <span class="font-medium text-xs">Uber</span>
      </div>
      
      <div class="absolute top-[60%] right-[10%] -translate-y-1/2 w-14 h-14 bg-[#FF5A5F] rounded-2xl flex items-center justify-center text-white shadow-sm z-10">
           <svg width="24" height="24" viewBox="0 0 24 24" fill="currentColor"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm0 18c-4.41 0-8-3.59-8-8s3.59-8 8-8 8 3.59 8 8-3.59 8-8 8zm-1-13h2v6h-2zm0 8h2v2h-2z"/></svg>
      </div>
      
      <div class="absolute top-[80%] right-[10%] -translate-y-1/2 w-14 h-14 bg-[#E11F26] rounded-2xl flex items-center justify-center text-white shadow-sm z-10">
          <div class="w-6 h-6 rounded-full border-4 border-white"></div>
          <div class="w-2 h-2 rounded-full bg-white absolute"></div>
      </div>

    </div>
  </div>
</section>
