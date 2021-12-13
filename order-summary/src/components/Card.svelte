<script>
  import Hero from "./Hero.svelte";
</script>

<div id="card">
  <Hero />
</div>

<style>
  #card {
    width: 400px;
    border-radius: 15px;
    box-shadow: 5px 5px 5px rgba(0, 0, 0, 0.5);
    background-color: white;
    position: fixed;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    overflow: hidden;
  }
</style>
