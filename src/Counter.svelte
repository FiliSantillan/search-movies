<script>
  export let initialCounter = 0;
  let count = initialCounter;

  function handleClick() {
    count++;
  }
</script>

<style>
  h1 {
    color: #ff3e00;
    text-transform: uppercase;
    font-size: 4em;
    font-weight: 100;
  }
</style>

<button on:click={handleClick}>Incrementar</button>
<h1>{count}</h1>
