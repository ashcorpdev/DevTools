<script context="module" lang="ts">
	export const prerender = true;
	import logo from '../lib/header/ashcorp_logo.png';
</script>

<script lang="ts">
	import { Button } from 'sveltestrap/src';
</script>

<svelte:head>
	<title>Home | AshCorp Twitch Tools</title>
</svelte:head>

<section>
	<h1 class="display-2">
		AshCorp
		<small class="text-muted">Twitch Tools</small>
	</h1>
	<p class="lead">A collection of tools designed to make streaming easier.</p>
	<p>Select a category from the menu above to get started.</p>
</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 1;
	}

	h1 {
		width: 100%;
	}
</style>
