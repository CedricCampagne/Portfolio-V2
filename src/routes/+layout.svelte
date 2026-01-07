<script>
  import '../app.css'; // ton CSS global
  import Navbar from '$lib/components/Navbar.svelte';
  import Footer from '$lib/components/Footer.svelte';
</script>

<div class="min-h-screen flex flex-col bg-slate-700 text-slate-100">
  <Navbar />

  <main class="grow container mx-auto mt-30 p-6 overflow-y-hidden">
    <slot />
  </main>

  <Footer />
</div>

