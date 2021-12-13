<script>
  import Hero from "./Hero.svelte";
  import Title from "./Title.svelte";
  import Plan from "./Plan.svelte";
</script>

<div id="card">
  <Hero />
  <Title />
  <Plan />
</div>

<style>
  #card {
    width: 400px;
    border-radius: 15px;
    box-shadow: 10px 10px 10px rgba(0, 0, 0, 0.25);
    background-color: white;
    position: fixed;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    overflow: hidden;
  }
</style>
