<script>
  export let color1 = "orange";
  export let color2 = " #ff964585";
</script>

<header>
  <h1 style="background: {color1}" class="Walls1">
    Walls <span class="te-reo-maori"> - Pātū </span>
  </h1>

  <h2 style="background: {color2};" class="Walls2">Website Containing Walls</h2>
</header>

<style>
  .te-reo-maori {
    font-style: italic;
  }
  header {
    display: flex;
  }

  h1 {
    font-family: "Passero One";
    font-size: 70px;
    width: 750px;
  }

  h2 {
    font-family: "Passero One";
    font-size: 55px;
    width: 750px;

    justify-content: right;
    align-items: end;
    display: flex;
  }

  @media screen and (max-width: 600px) {
    header {
      width: 600px;
    }
    h1 {
      font-size: 50px;
    }
    h2 {
      font-size: 35px;
    }
  }
</style>
