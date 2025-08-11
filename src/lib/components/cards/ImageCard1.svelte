<script>
    export let city = "Cidade"
    export let description = "Descrição"
    export let img = ""
    export let link = "href"
</script>

<div
  class="relative max-w-md aspect-[16:9] rounded-md overflow-hidden transition-all duration-100 shadow shadow-neutral-400 hover:-translate-y-1 hover:shadow-sky-400 cursor-pointer"
>
  <img
    src={img}
    alt="Paisagem"
    class="absolute inset-0 w-full h-full object-cover"
  />
  <div class="absolute inset-0 bg-black/60"></div>

  <div class="relative z-10 p-4">
    <h2 class="text-lg font-bold">{city}</h2>
    <p class="text-xs">
      {description}
    </p>
  </div>
</div>
