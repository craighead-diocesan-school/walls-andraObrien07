<script>
  import Header from "$lib/Header.svelte";
  import Footer from "$lib/Footer.svelte";
</script>

<Header />

<main>
  <h2>SvelteKit</h2>

  <div class="column">
    <div class="imgD">
      <img src="art-deco.jpeg" alt="Art Deco Wall" />
    </div>
    <p>Art Deco Wall</p>
    <p class="price">$34.9</p>
  </div>

  <div class="column">
    <div class="imgD">
      <img src="flowers-wall.jpeg" alt="Wall With Flower" />
    </div>
    <p>Wall With Flowers</p>
    <p class="price">$24.9</p>
  </div>

  <div class="column">
    <div class="imgD">
      <img src="grey-run-down.jpeg" alt="Run-Down Wall Painted Grey" />
    </div>
    <p>Run Down Wall Painted Grey</p>
    <p class="price">$4.9</p>
  </div>

  <div class="column">
    <div class="imgD">
      <img src="modified-white-brick.jpeg" alt="Brick Wall Painted White" />
    </div>
    <p>Brick Wall Painted White</p>
    <p class="price">$14.9</p>
  </div>

  <div class="column">
    <div class="imgD">
      <img src="orange-plaster.jpeg" alt="Plastered Wall Painted Orange" />
    </div>
    <p>Plastered Wall Painted Orange</p>
    <p class="price">$11.9</p>
  </div>

  <div class="column">
    <div class="imgD">
      <img src="pink-brick.jpeg" alt="Brick Wall Painted Pink" />
    </div>
    <p>Brick Wall Painted Pink</p>
    <p class="price">$19.9</p>
  </div>

  <div class="column">
    <div class="imgD">
      <img src="rough-wall.jpeg" alt="Really Rough Wall " />
    </div>
    <p>Really Rough Wall</p>
    <p class="price">$4.9</p>
  </div>

  <div class="column">
    <div class="imgD">
      <img src="tan-run-down.jpeg" alt="Run-Down Wall Painted Tan" />
    </div>
    <p>Run-Down Wall Painted Tan</p>
    <p class="price">$4.9</p>
  </div>

  <div class="column">
    <div class="imgD">
      <img src="unpainted-brick.jpeg" alt="Unpainted Brick Wall" />
    </div>
    <p>Unpainted Brick Wall</p>
    <p class="price">$9.9</p>
  </div>

  <div class="column">
    <div class="imgD">
      <img src="yellow-run-.jpeg" alt="Run-Down Wall Painted Yellow" />
    </div>
    <p class="name">Run-Down Wall Painted Yellow</p>
    <p class="price">$4.9</p>
  </div>
</main>

<Footer />

<style>
  .column {
    display: flex;
    align-items: center;
  }
  img {
    width: 80%;
  }

  p {
    font-family: "Passero One";
    font-size: 40px;
  }

  .imgD:hover {
    background-color: #ff964585;
    /* transition: 1s; */
  }
  .price:hover {
    background-color: #ff964585;
  }
  .name:hover {
    background-color: #ff964585;
  }

  .price {
    font-size: 35px;
  }
</style>
