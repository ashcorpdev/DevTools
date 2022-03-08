<script context="module" lang="ts">
	export const prerender = true;
</script>

<script lang="ts">
	import Card from '$lib/components/Card.svelte';
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
	<div class="album py-5">
		<div class="container">
			<div class="row row-cols-1 row-cols-sm-2 row-cols-md-2 g-3">
				<div class="col">
					<Card
					src="https://images.unsplash.com/photo-1565688842882-e0b2693d349a?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1170&q=80"	
					alt="Profile"
					title="Streamlabs Loyalty Exporter"
					text="A tool to export your Streamlabs Loyalty Extension points into a CSV file format."				
					link="https://github.com/ashcorpdev/sl-export"
					></Card>
				</div>
				<div class="col">
				</div>
				<div class="col">
				</div>
				<div class="col">
				</div>
				<div class="col">
				</div>
				<div class="col">
				</div>

				<div class="col">
				</div>
				<div class="col">
				</div>
				<div class="col">
				</div>
			</div>
		</div>
	</div>
</div>

<style>
	h1 {
		width: 100%;
	}
</style>
