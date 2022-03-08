<script context="module" lang="ts">
	export const prerender = true;
</script>

<script lang="ts">
	import { Button } from 'sveltestrap/src';
</script>

<svelte:head>
	<title>Loyalty Extension Exporter | AshCorp Twitch Tools</title>
</svelte:head>

<div class="row">
	<div class="col">
		<h1 class="display-5 pb-4">Loyalty Extension Exporter</h1>
	</div>
	<div class="row">
		<div class="col text-center">
			<p class="">
				Click the button below to export your loyalty extension points into a CSV file!
			</p>
			<Button>Click here!</Button>
		</div>
	</div>
	<div class="text-center">
		<div class="row">
			<div class="justify-content-center text-center mt-100 pt-5">
				<div class="col">
					<div class="file-area d-flex justify-content-center p-5">
						<p id="file-area-subtext" class="small" hidden>
							Once your file is ready, it will appear here...
						</p>
						<div id="download-link" class="col">
							<p class="small">Once your file is ready, it will appear here...</p>
							<Button>Download</Button>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</div>

<style>
	h1 {
		width: 100%;
	}

	.file-area {
		width: 450px;
		border: 1px dashed rgba(255, 255, 255, 0.4);
		border-radius: 3px;
		transition: 0.2s;
	}
</style>
