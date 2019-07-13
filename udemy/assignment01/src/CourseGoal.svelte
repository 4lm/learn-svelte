<script>
  export let goal;
</script>

<style>
  .exclamation {
    color: red;
  }
</style>

<h1 class={goal.includes('!') ? 'exclamation' : ''}>{goal}</h1>
