<script>
  import Header from "$lib/Header.svelte";
  import Footer from "$lib/Footer.svelte";
</script>

<Header />

<main>
  <div class="column">
    <img src="art-deco.jpeg" alt="Art Deco Wall" />
    <div class="words">
      <p class="name">Art Deco Wall</p>
      <p class="price">$34.9</p>
    </div>
  </div>

  <div class="column">
    <img src="flowers-wall.jpeg" alt="Wall With Flower" />
    <div class="words">
      <p class="name">Wall With Flowers</p>
      <p class="price">$24.9</p>
    </div>
  </div>

  <div class="column">
    <img src="grey-run-down.jpeg" alt="Run-Down Wall Painted Grey" />
    <div class="words">
      <p class="name">Run Down Wall Painted Grey</p>
      <p class="price">$4.9</p>
    </div>
  </div>

  <div class="column">
    <img src="modified-white-brick.jpeg" alt="Brick Wall Painted White" />
    <div class="words">
      <p class="name">Brick Wall Painted White</p>
      <p class="price">$14.9</p>
    </div>
  </div>

  <div class="column">
    <img src="orange-plaster.jpeg" alt="Plastered Wall Painted Orange" />
    <div class="words">
      <p class="name">Plastered Wall Painted Orange</p>
      <p class="price">$11.9</p>
    </div>
  </div>

  <div class="column">
    <img src="pink-brick.jpeg" alt="Brick Wall Painted Pink" />
    <div class="words">
      <p class="name">Brick Wall Painted Pink</p>
      <p class="price">$19.9</p>
    </div>
  </div>

  <div class="column">
    <img src="rough-wall.jpeg" alt="Really Rough Wall " />
    <div class="words">
      <p class="name">Really Rough Wall</p>
      <p class="price">$4.9</p>
    </div>
  </div>

  <div class="column">
    <img src="tan-run-down.jpeg" alt="Run-Down Wall Painted Tan" />
    <div class="words">
      <p class="name">Run-Down Wall Painted Tan</p>
      <p class="price">$4.9</p>
    </div>
  </div>

  <div class="column">
    <img src="unpainted-brick.jpeg" alt="Unpainted Brick Wall" />
    <div class="words">
      <p class="name">Unpainted Brick Wall</p>
      <p class="price">$9.9</p>
    </div>
  </div>

  <div class="column">
    <img src="yellow-run-.jpeg" alt="Run-Down Wall Painted Yellow" />
    <div class="words">
      <p class="name">Run-Down Wall Painted Yellow</p>
      <p class="price">$4.9</p>
    </div>
  </div>
</main>

<Footer />

<style>
  main {
    padding-left: 5%;
  }

  .words {
    margin-left: 60px;
    margin-top: 100px;
  }

  .column {
    display: flex;
    background-color: rgb(255, 255, 255);
    /* transition: 1s; */
  }
  img {
    width: 50%;
    margin-top: 20px;
    margin-bottom: 20px;
    /* border */
    border: 10px;
    border: #563030;
  }

  p {
    font-family: "Passero One";
    font-size: 40px;
    margin-bottom: 10px;
    width: fit-content;
  }

  .price {
    background-color: #dcbea4;
  }

  .price:hover {
    background-color: #ff964585;
  }

  .name {
    background-color: #dcbea4;
  }
  img:hover + div.words > p {
    background-color: #ff964585;
  }
  img:hover {
    /* change border color */

    border-color: #ff964585;
    background-color: #ff964585;
  }

  .price {
    font-size: 35px;
  }
</style>
