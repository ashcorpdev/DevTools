<script lang="ts">
	import Header from '$lib/header/Header.svelte';
	import '../app.css';
	import { Styles } from 'sveltestrap';

</script>

<Header />

<main>
	<slot />
</main>

<footer>
	<p>Created by ashen with love. Copyright 2022 ashen</p>
</footer>

<style>
	main {
		flex: 1;
		display: flex;
		flex-direction: column;
		padding: 1rem;
		width: 100%;
		max-width: 1024px;
		margin: 0 auto;
		box-sizing: border-box;
	}

	footer {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		padding: 20px;
	}

	@media (min-width: 480px) {
		footer {
			padding: 20px 0;
		}
	}
</style>
