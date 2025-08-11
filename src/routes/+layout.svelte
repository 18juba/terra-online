<script>
  import "../app.css";
  import favicon from "$lib/assets/favicon.svg";

  import "@fontsource/russo-one";
  import "@fontsource/google-sans-code";
  import "@fontsource/bitcount-prop-single";

  let { children } = $props();
</script>

<svelte:head>
  <link rel="icon" href={favicon} />
</svelte:head>

<main class="font2 relative min-h-screen">
  {@render children?.()}
</main>
