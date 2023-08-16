<script>
	import Section from "../container/Section.svelte";

  let playbackRate = 0.5;
</script>

<Section
  name="hero"
  className="flex min-h-screen items-center flex-col gap-4 md:flex-row justify-between">
  <div class="flex-1 p-4 flex flex-col gap-2">
    <h1 class="text-2xl md:text-4xl text-orange-500">
      Connecting Resources
    </h1>
    <p class="text-5xl font-bold">
      Your Partner in Hydrology, Borehole Drilling and Mining
    </p>
  </div>
  <div class="flex flex-col items-center md:items-end justify-center md:justify-end flex-[0.7] opacity-90">
    <video
      class="md:w-[30rem] w-[90vw] rounded-xl object-cover aspect-square"
      muted loop autoplay bind:playbackRate={playbackRate}
      src="/videos/water.mp4">
      <track kind="captions" />
    </video>
  </div>
</Section>
