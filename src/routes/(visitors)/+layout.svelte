<script>
  import AppShell from "$lib/components/container/AppShell.svelte";
	import Footer from "$lib/components/visitors/Footer.svelte";
  import Navbar from "$lib/components/visitors/Navbar.svelte";
</script>

<AppShell>
  <svelte:fragment slot="nav">
    <Navbar />
  </svelte:fragment>
  <div class="px-3 sm:px-10">
    <slot />
  </div>
  <svelte:fragment slot="footer">
    <Footer />
  </svelte:fragment>
</AppShell>
