<script>
	// import './styles.css';
	import '../app.css';
</script>

<div class="app">
	<main>
		<slot />
	</main>

	<footer class="footer p-10 bg-neutral text-neutral-content">
		<p>Yeehaw!</p>
	</footer>
</div>

<style lang="postcss">
	.app {
		display: flex;
		flex-direction: column;
		min-height: 100vh;
	}

	main {
		flex: 1;
		display: flex;
		flex-direction: column;
		padding: 1rem;
		width: 100%;
		max-width: 64rem;
		margin: 0 auto;
		box-sizing: border-box;
	}
</style>
