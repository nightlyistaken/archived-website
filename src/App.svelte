<script lang="ts">
  import Toggler from "./ViewMode.svelte";
</script>

<meta name="viewport" content="width=device-width,initial-scale=1" />

<title>Svelte app</title>
<ul id="menu">
  <li><a href="/">Home</a></li>
  <li><a href="/">About me</a></li>
  <li><Toggler>Toggle</Toggler></li>
</ul>

<main>
  <h1>Hello!</h1>
  <p>
    Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn
    how to build Svelte apps.
  </p>
</main>

<style lang="scss">
  @import "./styles/global.scss";
  @import "./styles/_darkMode.scss";
</style>
