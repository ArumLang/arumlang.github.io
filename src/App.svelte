<script lang="ts">
	import Topbar from "./components/Header.svelte";
	import Code from "./components/Code.svelte";
</script>

<main>
	<Topbar />
	<Code />

	<div class="align-left" style="margin: 8rem">
		<h2>Beginner friendly</h2>
		<p>Focus on making your syntax look sleet and concrete while<br>
			not making it hard for others to get into scripting.
		</p>
	</div>
	<div class="align-left" style="margin: 8rem; padding-bottom: 1rem;">
		<h2>Designed for places</h2>
		<p>Arum is designed for specific places like game engines<br>
			and modding, as well as general modding for games.<br>
			Arum is meant to be paired together with a game engine or game<br>
			however, you are able to use it standalone.
		</p>
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

	.align-right {
		text-align: right;
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

	h2 {
		color: #ffe4db;
		text-transform: uppercase;
		font-size: 3em;
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