<script>
  let name = 'Brian'

  const handleClick = () => {
    alert('Hello World')
  }
</script>

<main>
  <h1>{name}</h1>
  <button on:click={handleClick}>Click it!</button>
</main>