<script>
	import { Button } from "flowbite-svelte";
import Section from "../container/Section.svelte";

</script>
<Section name="about">
  <div class="flex items-start gap-10 flex-col relative">
    <span class="uppercase top-7 rotate-90 absolute text-orange-500 inline-flex">About Us</span>
    <div class="absolute top-0 right-2">
      <Button color="alternative" href="/#">See Our Services</Button>
    </div>
      
    <div class="ml-20 max-w-lg flex flex-col gap-4">
      <h2 class="font-bold text-3xl">
        We specialize in geo-resource investigation and exploration
      </h2>
      <p class="text-black/70">
        At Aquamark Integrated Services, we offer a range of services,
        including geophysical and hydrological surverys, water borehole
        drilling, mining and geotechincal soil investigation.
      </p>
    </div>
    <div class="ml-20 max-w-lg flex self-end flex-col gap-4">
      <h2 class="font-bold text-3xl">
        We are trusted
      </h2>
      <p class="text-black/70">
        We hold ourselves to the highest ethical standards, ensuring
        transparency and reliablity in all our interactions. 
        We Pride ourselves on delivering comprehensive services that
        exceed expectations, and our dedicated team ensures that every
        project is executed with utmost efficiency and precision.
      </p>
    </div>
  </div>
</Section>
