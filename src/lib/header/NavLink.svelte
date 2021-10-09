<script>
  import { page } from "$app/stores";

  export let href;
</script>

<a class="nav-link" sveltekit:prefetch {href} class:active={$page.path === href}
  ><slot /></a
>

<style lang="postcss">
  .nav-link {
    @apply text-lg pt-1.5 text-gray-500 transition-colors;
  }

  .nav-link:hover {
    @apply text-red-700;
  }

  .nav-link.active {
    @apply text-gray-900;
  }
</style>
