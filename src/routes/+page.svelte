<script>
  import Button1 from "$lib/components/actions/Button1.svelte";
  import IconButton1 from "$lib/components/actions/IconButton1.svelte";
</script>

<div
  class="h-screen flex flex-col justify-center items-center text-center text-white"
>
  <h1 class="font3 text-7xl">TERRA</h1>
  <a data-sveltekit-preload-data href="/dashboard">
    <Button1 text="Iniciar" />
  </a>
</div>
