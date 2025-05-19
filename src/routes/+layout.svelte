<script lang="ts">
	import "../app.css";
	let { children } = $props();
</script>

<div class="container">
	<header>
		<a href="/"><h1>kidrakaprint.ink</h1></a>
	</header>
	<main>
		{@render children()}
	</main>
</div>

<style>
	.container {
		display: block;
		max-width: 800px;
		margin: 0 auto;
	}
</style>
