<script context="module" lang="ts">
	export const prerender = true;
</script>

<script lang="ts">
	import Card from '../../lib/components/Card.svelte';
</script>

<svelte:head>
	<title>Streamlabs | AshCorp Twitch Tools</title>
</svelte:head>

<div class="container">
	<div class="row">
		<div class="col">
			<h1 class="display-5 pb-4">Streamlabs</h1>
		</div>
	</div>
    <div class="w-100"></div>
	<div class="row">
	<div class="col">
		<Card
			src="https://avatars.githubusercontent.com/u/5949532?v=4"
			alt="Ashen"
			title="AshCorpDev @ GitHub"
			text="Developer from the UK. Working on web applications for streamers on Twitch."
			link="https://github.com/ashcorpdev"
		/>
	</div>
	<div class="col">
		<Card
			src="https://avatars.githubusercontent.com/u/5949532?v=4"
			alt="Ashen"
			title="AshCorpDev @ GitHub"
			text="Developer from the UK. Working on web applications for streamers on Twitch."
			link="https://github.com/ashcorpdev"
		/>
	</div>
	</div>
	<div class="row">
	<div class="col">
		<Card
			src="https://avatars.githubusercontent.com/u/5949532?v=4"
			alt="Ashen"
			title="AshCorpDev @ GitHub"
			text="Developer from the UK. Working on web applications for streamers on Twitch."
			link="https://github.com/ashcorpdev"
		/>
	</div>
	<div class="col">
		<Card
			src="https://avatars.githubusercontent.com/u/5949532?v=4"
			alt="Ashen"
			title="AshCorpDev @ GitHub"
			text="Developer from the UK. Working on web applications for streamers on Twitch."
			link="https://github.com/ashcorpdev"
		/>
	</div>
	</div>
</div>

<style>
	h1 {
		width: 100%;
	}
</style>
