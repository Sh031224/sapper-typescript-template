<svelte:options immutable />

<style>
  h1 {
    text-align: center;
    color: dodgerblue;
    margin-top: 2rem;
  }
</style>

<script>
  export let title: string;
</script>

<h1>{title}</h1>
