<script lang="ts">
  let count = 0
  const increment = () => {
    count += 1
  }
  const decrement = () => {
    count -= 1
  }
</script>
<div class="card">
  <div class="card-body">
    <p class="font-monospace">Count is {count}</p>
  </div>
  <div class="container">
    <div class="row">
      <div class="col">
        <button type="button" class="btn btn-outline-primary" on:click={increment}>
          Click to count up
        </button>
      </div>
      <div class="col">
        <button type="button" class="btn btn-outline-primary" on:click={decrement}>
          click to count down
        </button>
      </div>
    </div>
  </div>
  </div>



