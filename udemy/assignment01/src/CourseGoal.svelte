<script>
  export let goal;

  $: hasExclamation = goal.includes("!");
</script>

<style>
  .exclamation {
    color: red;
  }
</style>

<h1 class:exclamation={hasExclamation}>{goal}</h1>
