<script>
  import NavLink from "./NavLink.svelte";
</script>

<div class="flex justify-center max-w-full overflow-hidden">
  <nav
    class="w-full max-w-screen-lg h-16 flex items-center space-x-2 sm:space-x-3 px-4 font-serif overflow-x-auto"
  >
    <h1 class="pr-1 sm:pr-2 pt-1.5 text-xl sm:text-2xl heading">
      <a href="/">confessions</a>
    </h1>
    <NavLink href="/">home</NavLink>
    <NavLink href="/new">new</NavLink>
    <NavLink href="/submit">submit</NavLink>
    <NavLink href="/search">search</NavLink>
  </nav>
</div>

<div class="h-0.5 gradient" />

<style lang="postcss">
  .gradient {
    @apply bg-gradient-to-r from-yellow-400 via-red-500 to-pink-500;
  }
</style>
