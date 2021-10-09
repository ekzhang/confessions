<script>
  import Header from "$lib/Header/Header.svelte";
  import "../app.css";
</script>

<Header />

<main>
  <slot />
</main>

<style lang="postcss">
  main {
    @apply max-w-screen-lg mx-auto p-4 overflow-x-hidden;
  }
</style>
