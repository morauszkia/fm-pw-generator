<script lang="ts">
  import Display from "./components/Display.svelte";
</script>

<main>
  <h1>Password Generator</h1>
  <Display />
</main>

<style>
  main {
    width: 100%;
  }

  h1 {
    font-size: 1rem;
    color: var(--text-grey);
    font-weight: 700;
    text-align: center;
    margin-bottom: 2rem;
  }
</style>
