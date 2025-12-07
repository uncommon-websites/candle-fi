<script lang="ts">
  import Navbar from '$lib/components/Navbar.svelte';
  import Hero from '$lib/components/Hero.svelte';
  import GetItAll from '$lib/components/GetItAll.svelte';
  import TakeAction from '$lib/components/TakeAction.svelte';
  import LevelUp from '$lib/components/LevelUp.svelte';
  import FAQ from '$lib/components/FAQ.svelte';
  import Footer from '$lib/components/Footer.svelte';
  import BuildApps from '$lib/components/BuildApps.svelte';
</script>

<div class="min-h-screen flex flex-col items-center w-full overflow-x-hidden">
  <Navbar />
  <main class="w-full flex flex-col items-center">
    <Hero />
    <GetItAll />
    <TakeAction />
    <LevelUp />
    <FAQ />
    <BuildApps />
  </main>
  <Footer />
</div>

