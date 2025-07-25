<!-- Minimal Svelte app: displays one line of centered text in a simple, light theme -->

<script>
	// No JS needed for this minimal page
</script>

<main>
	<p class="center-text">
		Hello, this is a minimal Svelte app.
	</p>
</main>

<style>
	main {
		height: 100vh;
		display: flex;
		align-items: center;
		justify-content: center;
		background: #f9fafb;
		margin: 0;
	}
	.center-text {
		font-size: 1.5rem;
		color: #222;
		text-align: center;
		font-family: Arial, Helvetica, sans-serif;
		font-weight: 400;
		letter-spacing: 0.02em;
	}
</style>
