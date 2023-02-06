<script>
	import Counter from './Counter.svelte';
	import welcome from '$lib/images/svelte-welcome.webp';
	import welcome_fallback from '$lib/images/svelte-welcome.png';
	import Navbar from './Navbar.svelte';
	import { Alert } from 'flowbite-svelte';
	import { Card } from 'flowbite-svelte';
	import ProgressBar from './replay/ProgressBar.svelte';
	import SearchBar from './search/SearchBar.svelte';
</script>






<section>


<div>
  <Card href="/rule">
    <h2 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white text-center">26</h2>
    <p class="font-normal text-gray-700 dark:text-gray-400 leading-tight">
      C&C not fulfilelled
    </p>
  </Card>
	
	  <Card href="/rule">
    <h2 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white text-center">18</h2>
    <p class="font-normal text-gray-700 dark:text-gray-400 leading-tight">
      Still in CREATED
    </p>
  </Card>
</div>





</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 0.6;
	}

	h1 {
		width: 100%;
	}

	.welcome {
		display: block;
		position: relative;
		width: 100%;
		height: 0;
		padding: 0 0 calc(100% * 495 / 2048) 0;
	}

	.welcome img {
		position: absolute;
		width: 100%;
		height: 100%;
		top: 0;
		display: block;
	}
</style>
