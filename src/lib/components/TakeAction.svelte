<script>
  // TakeAction component with Feature Cards
</script>

<section class="py-20 px-4 w-full max-w-7xl mx-auto">
  <div class="mb-16 max-w-2xl">
    <span class="text-[#FF5A4F] font-medium mb-4 block">Write</span>
    <h2 class="text-4xl md:text-5xl font-bold text-gray-900 mb-4">Take Action</h2>
    <p class="text-gray-500 text-lg">Programmatically interact with the real world — automate tasks, fulfill requests, and move value.</p>
  </div>

  <div class="space-y-8">
    <!-- Card 1: Book Rides + Rentals -->
    <div class="bg-[#F9FAFB] rounded-[2rem] p-10 relative overflow-hidden">
      <div class="flex flex-col md:flex-row justify-between items-start gap-8">
        <div class="max-w-md z-10">
          <h3 class="text-3xl font-bold text-gray-900 mb-6">Book Rides + Rentals</h3>
          <ul class="space-y-3 mb-8">
            {#each ['Get real-time prices', 'Compare across apps', 'Track in-progress trips'] as item}
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
        </div>
        <button class="bg-white border border-gray-200 px-4 py-2 rounded-full text-sm font-medium hover:bg-gray-50 transition-colors flex items-center gap-2 z-10 self-start md:self-center">
          See example code
          <svg class="w-3 h-3" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
            <path d="M7 17L17 7M17 7H7M17 7V17" stroke-linecap="round" stroke-linejoin="round"/>
          </svg>
        </button>
      </div>
      
      <div class="mt-12 flex gap-4 overflow-hidden mask-linear-fade">
        <!-- Icons Row -->
        <div class="w-12 h-12 bg-black rounded-xl flex items-center justify-center text-white text-[10px]">Uber</div>
        <div class="w-12 h-12 bg-[#FF00BF] rounded-xl flex items-center justify-center text-white font-bold text-xs">lyft</div>
        <div class="w-12 h-12 bg-[#00D1D1] rounded-xl flex items-center justify-center text-white font-bold text-lg">w</div>
        <div class="w-12 h-12 bg-[#00A4E0] rounded-xl flex items-center justify-center text-white font-bold text-xs">revel</div>
        <div class="w-12 h-12 bg-black rounded-xl flex items-center justify-center text-white font-bold text-xs">TURO</div>
        <div class="w-12 h-12 bg-[#A633D6] rounded-xl flex items-center justify-center text-white font-bold text-lg">g</div>
        <div class="w-12 h-12 bg-[#4F9D46] rounded-xl flex items-center justify-center text-white font-bold text-lg">Z</div>
      </div>
    </div>

    <!-- Card 2: Trade Stocks + Crypto -->
    <div class="bg-[#F9FAFB] rounded-[2rem] p-10 relative overflow-hidden">
      <div class="flex flex-col md:flex-row justify-between items-start gap-8">
        <!-- Button on Left for this one? Screenshot shows button left, text right. -->
        <div class="order-2 md:order-1 self-start md:self-center">
            <button class="bg-white border border-gray-200 px-4 py-2 rounded-full text-sm font-medium hover:bg-gray-50 transition-colors flex items-center gap-2">
                See example code
                <svg class="w-3 h-3" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                  <path d="M7 17L17 7M17 7H7M17 7V17" stroke-linecap="round" stroke-linejoin="round"/>
                </svg>
            </button>
        </div>

        <div class="max-w-md z-10 order-1 md:order-2 text-left md:text-right ml-auto">
          <h3 class="text-3xl font-bold text-gray-900 mb-6">Trade Stocks + Crypto</h3>
          <ul class="space-y-3 mb-8 flex flex-col items-start md:items-end">
            {#each ['Get real-time prices', 'Compare across apps', 'Trade programmatically'] as item}
              <li class="flex items-center gap-3 flex-row-reverse md:flex-row">
                <span class="text-gray-700 font-medium">{item}</span>
                <div class="w-5 h-5 rounded-full bg-[#FFF0EF] flex items-center justify-center shrink-0">
                  <svg width="10" height="8" viewBox="0 0 10 8" fill="none">
                    <path d="M1 4L3.5 6.5L9 1" stroke="#FF5A4F" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                  </svg>
                </div>
              </li>
            {/each}
          </ul>
        </div>
      </div>
      
      <div class="mt-12 flex gap-4 justify-end">
        <!-- Icons Row -->
        <div class="w-12 h-12 bg-[#C3F53C] rounded-xl flex items-center justify-center text-black font-bold">
            <svg width="24" height="24" viewBox="0 0 24 24" fill="currentColor"><path d="M12 2L2 22h20L12 2zm0 4l6 12H6l6-12z"/></svg>
        </div>
        <div class="w-12 h-12 bg-[#0052FF] rounded-xl flex items-center justify-center text-white font-bold text-xl">C</div>
        <div class="w-12 h-12 bg-[#00D54B] rounded-xl flex items-center justify-center text-white font-bold text-xl">$</div>
        <div class="w-12 h-12 bg-[#BD1332] rounded-xl flex items-center justify-center text-white font-bold text-xl">V</div>
        <div class="w-12 h-12 bg-[#00A0DF] rounded-xl flex items-center justify-center text-white text-[8px] text-center p-1 leading-tight">Charles Schwab</div>
        <div class="w-12 h-12 bg-[#117ACA] rounded-xl flex items-center justify-center text-white font-bold">
            <div class="w-6 h-6 border-2 border-white rounded-none"></div>
        </div>
        <div class="w-12 h-12 bg-white border border-gray-200 rounded-xl flex items-center justify-center text-[#E31837] font-bold text-xs">
            BOA
        </div>
      </div>
    </div>

    <!-- Card 3: Send + Receive Money -->
    <div class="bg-[#F9FAFB] rounded-[2rem] p-10 relative overflow-hidden">
      <div class="flex flex-col md:flex-row justify-between items-start gap-8">
        <div class="max-w-md z-10">
          <h3 class="text-3xl font-bold text-gray-900 mb-6">Send + Receive Money</h3>
          <ul class="space-y-3 mb-8">
            {#each ['Find people by name or username', 'Compare fees', 'Share receive link'] as item}
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
        </div>
        <button class="bg-white border border-gray-200 px-4 py-2 rounded-full text-sm font-medium hover:bg-gray-50 transition-colors flex items-center gap-2 z-10 self-start md:self-center">
          See example code
          <svg class="w-3 h-3" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
            <path d="M7 17L17 7M17 7H7M17 7V17" stroke-linecap="round" stroke-linejoin="round"/>
          </svg>
        </button>
      </div>
      
      <div class="mt-12 flex gap-4">
        <!-- Icons Row -->
        <div class="w-12 h-12 bg-[#008CFF] rounded-xl flex items-center justify-center text-white font-bold text-xl">V</div>
        <div class="w-12 h-12 bg-[#003087] rounded-xl flex items-center justify-center text-white font-bold text-xl">P</div>
        <div class="w-12 h-12 bg-[#2E4053] rounded-xl flex items-center justify-center text-[#F5B041] font-bold text-xs border-t-4 border-[#F5B041]">Wise</div>
        <div class="w-12 h-12 bg-[#00D54B] rounded-xl flex items-center justify-center text-white font-bold text-xl">$</div>
        <div class="w-12 h-12 bg-[#00C88C] rounded-xl flex items-center justify-center text-white font-bold text-xl">C</div>
        <div class="w-12 h-12 bg-[#CD1409] rounded-xl flex items-center justify-center text-white font-bold text-xl">WF</div>
        <div class="w-12 h-12 bg-[#FF6600] rounded-xl flex items-center justify-center text-white font-bold text-[8px] uppercase tracking-tighter">Discover</div>
      </div>
    </div>
  </div>
</section>
