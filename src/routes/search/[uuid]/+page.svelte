<script>


import { page } from '$app/stores';
$page.url.pathname

var url = $page.url.pathname;
var lastPart = url.substring(url.lastIndexOf("/") + 1);




let query = lastPart;
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

	let x = search();

</script>

<p>L'URL de la page actuelle est: {$page.url.pathname}</p>

<div>
	<code>
<h1>{JSON.stringify(searchResult[0])}</h1> 
</code>
</div>

