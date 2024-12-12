<script>
  import Card from './lib/Card.svelte'
  import SearchBar from './lib/Search.svelte'
  import Bottom from './lib/bottom.svelte'
</script>


<main>

  <div class="container">
    <SearchBar />
    <h1>Gimnasios</h1>
    <Card />
    <Card />
    <Card />
    <Bottom/>
  </div>

</main>

<style>
  .container{
    display: flex;
    flex-direction: column;
    flex-wrap: wrap;
    background-color: white;
    border-radius: 15px;
    text-align: left;
  }

  h1{
    color: black;
  }
</style>
