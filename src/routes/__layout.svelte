<script>
	import '../app.css';
</script>

<div>
	<slot />
</div>

<style>
	:global(body) {
		margin: 0;
		padding: 0;
		background: var(--gradient-4);
	}

	div {
		display: grid;
		place-items: center;
		height: 100vh;
	}
</style>
