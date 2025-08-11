<script>
  export let icon = null;
  export let text = "";
</script>

<button
  aria-label={text}
  class="font3 rounded-full border-2 border-white/10 text-sky-400 p-2 cursor-pointer
         shadow-sm shadow-neutral-700 transition-all duration-100 hover:shadow-sky-400 hover:text-sky-500
         flex items-center justify-center"
>
  {#if icon}
    <svelte:component this={icon} class="w-6 h-6" />
  {/if}
</button>
