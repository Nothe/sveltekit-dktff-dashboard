<script>
	import '../app.postcss';
	import Header from './Header.svelte';
	import './styles.css';
	import Navbar from './Navbar.svelte';
</script>

<div class="app">
	<Navbar />
	<main>
		<slot />
	</main>


</div>

<style>
	.app {
		display: grid;
		grid-template-areas:
			'navbar main main '
			'navbar  main main'
			'navbar  main main'
			'navbar main main';
		grid-template-columns: 240px 1fr 1fr;
		grid-template-rows: 100px 1fr 1fr 1fr;
		height: 100vh;
		width: 100vw;
	}

	main {
		flex: 1;
		display: flex;
		flex-direction: column;
		padding: 1rem;
		width: 100%;
		max-width: 64rem;
		margin: 0 auto;
		box-sizing: border-box;
		grid-area: main;
	}

	footer {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		padding: 12px;
		background-color: grey;
		grid-area: footer;
	}

	footer a {
		font-weight: bold;
	}

	@media (min-width: 480px) {
		footer {
			padding: 12px 0;
		}
	}
</style>
