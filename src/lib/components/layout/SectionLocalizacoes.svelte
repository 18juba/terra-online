<script>
  import ImageCard1 from "../cards/ImageCard1.svelte";
</script>

<section class="p-20 flex flex-col gap-12 text-white">
  <div class="flex flex-col">
    <h1 class="font1 text-3xl mb-2">
      Brasil <span class="text-xs text-neutral-400">Brazil</span>
    </h1>
    <div class="flex gap-12">
      <ImageCard1
        city="Fortaleza"
        description="A capital do Ceará é famosa por suas praias e cultura vibrante"
        img="https://turismo.b-cdn.net/wp-content/uploads/2013/01/Fortaleza-a-capital-do-Ceara.webp"
      />
      <ImageCard1
        city="Manaus"
        description="Localizada no coração da Amazônia, famosa por sua rica história, cultura diversificada e paisagens naturais deslumbrantes"
        img="https://upload.wikimedia.org/wikipedia/commons/thumb/f/f8/Manaus_amazonas.jpg/1200px-Manaus_amazonas.jpg"
      />
      <ImageCard1
        city="Xique-Xique"
        description="A origem do nome Xique-Xique está associada à abundância de cactos do tipo xiquexique encontrados pelos primeiros colonizadores da região"
        img="https://upload.wikimedia.org/wikipedia/commons/4/45/Webysther_20150906180926_-_Vista_da_igreja_matriz_xique-xique.jpg"
      />
    </div>
  </div>

  <div class="flex flex-col">
    <h1 class="font1 text-3xl mb-2">
      España <span class="text-xs text-neutral-400">Spain</span>
    </h1>
    <div class="flex gap-12">
      <ImageCard1
        city="Sevilla"
        description="Su patrimonio histórico y monumental y sus diversos espacios escénicos y culturales la convierten en una ciudad receptora de turismo nacional e internacional"
        img="https://www.spain.info/export/sites/segtur/.content/imagenes/rutas/dos-dias-sevilla/torre-oro-sevilla-s444797035.jpg_1224728085.jpg"
      />
    </div>
  </div>

  <div class="flex flex-col">
    <h1 class="font1 text-3xl mb-2">
      Deutschland <span class="text-xs text-neutral-400">Germany</span>
    </h1>
    <div class="flex gap-12">
      <ImageCard1
        city="München"
        description="München ist bekannt für seine Mischung aus Tradition und Moderne, Kunst und Kultur,"
        img="https://img.static-kl.com/images/media/8408DCFF-A031-41AA-80E115AAEC965C24"
      />
    </div>
  </div>
</section>
