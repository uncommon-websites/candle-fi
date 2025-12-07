<script>
  // Navbar component
</script>

<nav class="fixed top-6 z-50">
  <div class="bg-gray-100/80 backdrop-blur-md border border-white/20 rounded-full px-6 py-3 flex items-center gap-8 shadow-sm">
    <a href="/" class="flex items-center gap-2 font-semibold text-lg text-black">
      <div class="w-8 h-8 rounded-full bg-black flex items-center justify-center relative overflow-hidden">
        <!-- Candle Logo -->
        <svg width="16" height="16" viewBox="0 0 24 24" fill="white">
            <path d="M12 2C12 2 6 8 6 13C6 16.3137 8.68629 19 12 19C15.3137 19 18 16.3137 18 13C18 8 12 2 12 2Z" />
            <circle cx="12" cy="13" r="3" fill="black" fill-opacity="0.2"/>
        </svg>
        <div class="absolute inset-0 rounded-full border border-white/10"></div>
      </div>
      Candle
    </a>
    
    <div class="flex items-center gap-6 text-sm font-medium text-gray-600">
      <a href="#pricing" class="hover:text-black transition-colors">Pricing</a>
      <a href="#docs" class="hover:text-black transition-colors">Documentation</a>
      <a href="#signin" class="hover:text-black transition-colors">Sign In</a>
    </div>
  </div>
</nav>
