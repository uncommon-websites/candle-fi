<script>
  // FAQ component
  let openIndex = 0; // Default first one open? Screenshot doesn't show open, but usually one is. Actually screenshot shows all closed or just titles. Let's assume closed or interactive.
  // Wait, looking at the screenshot, the "+" signs are red.
  
  const faqs = [
    { question: "How do you secure user data?", answer: "We use bank-grade encryption and never store credentials in plain text." },
    { question: "How are you different from other data aggregators?", answer: "We focus on write-access and automation, not just read-only data." },
    { question: "Do you use browser automation?", answer: "Yes, for some integrations where official APIs are not available, ensuring reliability." }
  ];
</script>

<section class="py-20 px-4 w-full max-w-7xl mx-auto">
  <div class="flex flex-col lg:flex-row gap-12 lg:gap-32">
    <div class="max-w-xs">
      <h2 class="text-4xl font-bold text-gray-900 leading-tight">
        Frequently<br>
        Asked<br>
        Questions
      </h2>
    </div>

    <div class="flex-1 border-t border-gray-200">
      {#each faqs as faq, i}
        <div class="border-b border-gray-200 py-6 group cursor-pointer">
          <div class="flex justify-between items-center">
            <h3 class="text-lg text-gray-700 font-medium group-hover:text-gray-900 transition-colors">{faq.question}</h3>
            <span class="text-[#FF5A4F] text-2xl font-light">+</span>
          </div>
        </div>
      {/each}
      
      <div class="mt-8">
        <a href="#faqs" class="text-[#FF5A4F] font-medium flex items-center gap-2 hover:gap-3 transition-all">
          See More FAQs
          <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
            <path d="M5 12h14M12 5l7 7-7 7" stroke-linecap="round" stroke-linejoin="round"/>
          </svg>
        </a>
      </div>
    </div>
  </div>
</section>
