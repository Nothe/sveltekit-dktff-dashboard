<script>

	import { Search } from 'flowbite-svelte';
  import { Button } from 'flowbite-svelte';

  let query = '';
  let result = '';
  let searchResult = [];

  async function search() {
    const response = await fetch(`https://LH9FQBCUWJ.algolia.net/1/indexes/indexation-test/?query=${query}`, {
      method: "GET",
      withCredentials: true,
      headers: {
        "X-Algolia-Application-Id": "LH9FQBCUWJ",
        "X-Algolia-API-Key": "4255b300ee6ebcc2184c1c810cde8516"
      }
    });
    result = await response.json();
    searchResult = result.hits;
  }
</script>

<div>
<h1 class="pt-12 pb-12">Search</h1>
	<form class="flex gap-2 w-full">
  <Search size="md" bind:value={query} on:keyup={search} />
    <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"/></svg>
	</form>
</div>

<button type="button" on:click={check}>Click Me!</button>

<input type="text" bind:value={query} />
<button on:click={search}>Rechercher</button>

{#each searchResult as result}
  <div>
    <h3>{result.container_id}</h3>
    <p>{result.order_id}</p>
  </div>
{/each}