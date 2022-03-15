<script lang="ts">
	import Topbar from "./components/Header.svelte";
</script>

<main>
	<Topbar />

	<div class="align-left" style="padding: 4rem">
		<h1>Arum</h1>
		<p>A beginner friendly scripting language</p>
	</div>
</main>

<style lang="scss">
	@import url('https://fonts.googleapis.com/css2?family=Fredoka:wght@300&display=swap');
	main {
		text-align: center;

		font-family: 'Fredoka', sans-serif;

		// padding: 1em;
		padding: 0px;
		max-width: 240px;
		margin: 0 auto;
	}

	.align-left {
		text-align: left;
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