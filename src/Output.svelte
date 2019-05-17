<script>
  export let courseGoal;
</script>

<style>
  .red-text {
    color: red;
  }
</style>

<h1 class:red-text={courseGoal.indexOf('!') > -1}>{courseGoal}</h1>
