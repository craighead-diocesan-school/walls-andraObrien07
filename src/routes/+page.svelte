<script>
  import Header from "$lib/Header.svelte";
  import Footer from "$lib/Footer.svelte";
  import Card from "$lib/Card.svelte";
</script>

<Header />

<main>
  <Card
    src="art-deco.jpeg"
    alt="Art Deco Wall"
    caption="Art Deco Wall"
    Maori="Kōwaiwai"
    money="34.9"
  />

  <Card
    src="flowers-wall.jpeg"
    alt="Wall With Flowers"
    caption="Wall With Flowers"
    Maori="PutiPuti"
    money="24.9"
  />

  <Card
    src="grey-run-down.jpeg"
    alt="Run-Down Wall Painted Grey"
    caption="Run Down Wall Painted Grey"
    Maori="Pakarukaru Kiwikiwi"
    money="4.9"
  />
  <Card
    src="modified-white-brick.jpeg"
    alt="Brick Wall Painted White"
    caption="Brick Wall Painted White"
    Maori="Mā"
    money="14.9"
  />

  <Card
    src="orange-plaster.jpeg"
    alt="Plastered Wall Painted Orange"
    caption="Plastered Wall Painted Orange"
    Maori="Karaka"
    money="11.9"
  />

  <Card
    src="pink-brick.jpeg"
    alt="Brick Wall Painted Pink"
    caption="Brick Wall Painted Pink"
    Maori="Māwhero"
    money="19.9"
  />

  <Card
    src="rough-wall.jpeg"
    alt="Really Rough Wall"
    caption="Brick Wall Painted Pink"
    Maori="Mātoretore"
    money="4.9"
  />

  <Card
    src="tan-run-down.jpeg"
    alt="Run-Down Wall Painted Tan"
    caption="Run Down Wall Painted Tan"
    Maori="Pakarukaru Parauri"
    money="4.9"
  />

  <Card
    src="unpainted-brick.jpeg"
    alt="Unpainted Brick Wall"
    caption="Unpainted Brick Wall"
    Maori="pātū tāwāhi"
    money="9.9"
  />

  <Card
    src="yellow-run-.jpeg"
    alt="Run-Down Wall Painted Yellow"
    caption="Run Down Wall Painted Yellow"
    Maori="Pakarukaru Kōwhai"
    money="4.9"
  />
</main>

<Footer />

<style>
  main {
    padding-left: 5%;
  }

  @media screen and (max-width: 600px) {
    main {
      flex-direction: column;
      align-items: center;
    }
  }
</style>
