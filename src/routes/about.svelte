<script context="module">
	import { browser, dev } from '$app/env';

	// we don't need any JS on this page, though we'll load
	// it in dev so that we get hot module replacement...
	export const hydrate = dev;

	// ...but if the client-side router is already loaded
	// (i.e. we came here from elsewhere in the app), use it
	export const router = browser;

	// since there's no dynamic data here, we can prerender
	// it so that it gets served as a static asset in prod
	export const prerender = true;
	import Card from '../lib/components/Card.svelte';
</script>

<svelte:head>
	<title>About | AshCorp Twitch Tools</title>
</svelte:head>

<div class="content">
	<h1 class="display-5">About this site</h1>

	<p>
		This is a site featuring a number of tools that I've developed to help make streaming life
		easier. You can find the source code to these tools over at my GitHub:
	</p>

	<Card
		src="https://avatars.githubusercontent.com/u/5949532?v=4"
		alt="Ashen"
		title="AshCorpDev @ GitHub"
		text="Developer from the UK. Working on web applications for streamers on Twitch."
		link="https://github.com/ashcorpdev"
	/>

	<p>
		Please be aware that this site <strong><em>does not</em></strong> store any credentials for privacy
		reasons. All tools require you to grant them access via the respective service they are intended
		for.
	</p>
</div>

<style>
	.content {
		width: 100%;
		max-width: var(--column-width);
		margin: var(--column-margin-top) auto 0 auto;
	}
</style>
