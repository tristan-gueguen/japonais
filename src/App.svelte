<script>
	import { Router, Link, Route } from "svelte-routing";
	import Adverbs from "./pages/Adverbs.svelte";
	import Kana from "./pages/Kana.svelte";
	import Verbs from "./pages/Verbs.svelte";
	
  export let url = "";
</script>

<Router url="{url}">
	<nav>
	<Link to="/adverbs">Adverbes</Link>
	<Link to="/kana">Kana</Link>
	<Link to="/verbs">Verbes</Link>
</nav>
	<main>
		<Route path="adverbs" component="{Adverbs}" />
		<Route path="kana" component="{Kana}" />
		<Route path="verbs" component="{Verbs}" />
	</main>
</Router>

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