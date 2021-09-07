<script lang="ts">
  import Toggler from "./ViewMode.svelte";
</script>

<div class="animate__fadeIn">
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <link
    rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"
  />
  <title>Svelte app</title>
  <ul id="menu">
    <li><a href="/">Home</a></li>
    <li><a href="/">About me</a></li>
    <li><Toggler>Toggle</Toggler></li>
  </ul>

  <main>
    <h1 class="animate__animated animate__tada" on:mousedown={animateMe}>
      Hello!
    </h1>
    <p>
      Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn
      how to build Svelte apps.
    </p>
  </main>
</div>

<style lang="scss">
  @import "./styles/global.scss";
  @import "./styles/_darkMode.scss";
</style>
