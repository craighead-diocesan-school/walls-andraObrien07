<script>
  export let color1 = "orange";
  export let color2 = " #ff964585";
</script>

<header>
  <h1 style="background: {color1}" class="Walls1">Walls</h1>

  <h2 style="background: {color2};" class="Walls2">Website Containing Walls</h2>
</header>

<style>
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
</style>
