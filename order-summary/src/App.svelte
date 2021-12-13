<script>
  import Card from "./components/Card.svelte";
</script>

<svelte:head>
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link
    href="https://fonts.googleapis.com/css2?family=Outfit:wght@300;400;600&display=swap"
    rel="stylesheet"
  />
</svelte:head>

<div id="main">
  <Card />
</div>

<style>
  #main {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: hsl(215, 51%, 70%);
  }
</style>
