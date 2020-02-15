<script>
  import Nav from "../components/Nav.svelte";

  export let segment;
</script>

<style>
  main {
    display: grid;
    grid-template-columns: 1fr 3fr;
    box-sizing: border-box;
  }
</style>

<Nav {segment} />

<main>
  <slot />
</main>
