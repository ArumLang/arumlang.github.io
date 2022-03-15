<script lang="ts">
	import Topbar from "./components/Header.svelte";
</script>

<main>
	<Topbar />

	<h1>Arum</h1>
	<p>A beginner friendly scripting language</p>
</main>

<style lang="scss">
	main {
		text-align: center;
		// padding: 1em;
		padding: 0px;
		max-width: 240px;
		margin: 0 auto;
	}

	body {
		padding: 0px;
	}

	h1 {
		color: #ffe4db;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	p {
		color: #fff;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>