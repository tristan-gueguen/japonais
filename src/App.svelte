<script>
	import Adverbs from "./pages/Adverbs.svelte";
</script>

<main>
	<Adverbs />
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	@media (min-width: 640px) {
		main {
			max-width: 800px;
		}
	}
</style>