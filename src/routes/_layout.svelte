<script>
  import Nav from "../components/Nav.svelte";

  export let segment;
</script>

<style>

</style>

<div id="page-wrapper">
  <Nav {segment} />

  <main>
    <slot />
  </main>
</div>
