<script lang="ts">
  export let name: string | null = null;
  export let className: string | null = null;
</script>

<section
  aria-label={name}
  class={`min-h-screen flex flex-col justify-center ${className}`}>
  <slot />
</section>
