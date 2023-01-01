<script>
  export let message
  export let title
</script>

<div class="card">
  <h2>{title}</h2>
  {@html message}
  <hr>
</div>

<style>
  .card {
    margin-bottom: 5rem;
    
  }

  hr {
    margin-top: 2rem;
  }
  
</style>