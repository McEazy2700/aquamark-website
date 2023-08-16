<main class="max-h-screen overflow-y-scroll">
  <div class="absolute w-full z-20 top-0 left-0 border-b">
    <slot name="nav" />
  </div>
  <div class="mt-20 md:mt-7">
    <slot />
  </div>
  <div>
    <slot name="footer" />
  </div>
</main>
