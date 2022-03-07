<script>
    export let src = "url";
    export let alt = "alt";
	export let title = "title"
	export let text = "Lorem ipsum"
	export let link = "https://google.com"
</script>
<div class="card mb-3" style="max-width: 540px; min-width: 400px;">
	<div class="row g-0">
		<div class="col-md-4">
			<img
				src={src}
				class="img-fluid rounded-start"
				alt={alt}
			/>
		</div>
		<div class="col-md-8">
			<div class="card-body">
				<h5 class="text-dark card-title">{title}</h5>
				<p class="text-dark card-text">
					{text}
				</p>
				<p class="text-dark card-text">
					<small class="text-muted"
						><a href={link} target="_blank">{link}</a></small
					>
				</p>
			</div>
		</div>
	</div>
</div>
