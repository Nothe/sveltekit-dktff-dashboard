<script>
	import SearchBar from './SearchBar.svelte';
	import { Search } from 'flowbite-svelte';
  import { Button } from 'flowbite-svelte';
	import List from './List.svelte';
	import HitCard from "./hitCard.svelte";

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

			<div class="search">
				<input type="text" class="search__input" placeholder="Search..." />
				<button class="search__button" />
			</div>

<div>
<h1 class=" pt-12 pb-12">Search</h1>
	<form class="flex gap-2 w-full">
  <Search size="md" bind:value={query} on:keyup={search} />
    <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"/></svg>
	</form>
</div>




{#each searchResult as hit}
  <div>
		<HitCard {hit}/>
  </div>
{/each}



<style>


	.search {
		with: 100%;
		position: relative;
	}

	.search__input {
		width: 100%;
		padding: 0.5rem 0.5rem 0.5rem 2rem;
		border-radius: 0.25rem;
		background-color: rgb(100 100 100 / 8%);
		display: block;
		color: var(--color-text);
		position: relative;
		border: 1px solid transparent;
	}

	.search__input:focus {
		outline: none;
		border: 1px solid var(--color-text);
	}

	.search__button {
		width: auto;
		height: 100%;
		aspect-ratio: 1;
		display: block;
		position: absolute;
		top: 0;
		left: 0;
		border: none;
		background-color: var(--color-text);
		mask-position: center;
		-webkit-mask-position: center;
		mask-size: 50%;
		-webkit-mask-size: 50%;
		mask-repeat: no-repeat;
		-webkit-mask-repeat: no-repeat;
		mask-image: var(--icon-search);
		-webkit-mask-image: var(--icon-search);
	}


</style>