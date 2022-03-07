<script>
    export let src = "url";
    export let alt = "alt";
	export let title = "title"
	export let text = "Lorem ipsum"
	export let link = "https://google.com"
</script>
<div class="card mb-3 bg-dark">
	<div class="row g-0">
		<div class="col-md-4">
			<img style="height: 170px; object-fit: cover;"
				src={src}
				class="img-fluid rounded-start"
				alt={alt}
			/>
		</div>
		<div class="col-md-8">
			<div class="card-body">
				<h5 class=" text-light card-title text-truncate">{title}</h5>
				<p class="text-light card-text text-truncate" style="max-height: 120px; white-space: pre-line;">
					{text}
					<small class="text-muted-2">
						<span>
						<a href={link} target="_blank">
							<br>
							{link}
						</a></span></small
					>
				</p>
			</div>
		</div>
	</div>
</div>
