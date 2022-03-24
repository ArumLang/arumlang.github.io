<header style="height: 7rem;">
	<!-- TODO: switch CDN from discord lmao -->
	<h1 style="display: flex; justify-content: space-around">
		<img src="/favicon.png" alt="ArumLogo" />
		<div id="wrapper" style="float: right; display: inline-block; display: flex; justify-content: center">
			<button style="max-width: 1rem, height:4rem; text-align: center;" onclick="location.href='https://discord.gg/gCGmraBRQ8'">
				Discord
			</button>
			<button style="max-width: 1rem, height:4rem; text-align: center;" onclick="location.href='https://github.com/ArumLang'">
				Github
			</button>
		</div>
	</h1>
</header>

<style lang="scss">
	header {
		background-color: #333;
		// padding-left: 17.5rem;
	}

	#wrapper {
		display: flex;
		flex-direction: row;
		justify-content: center;
		align-items: center;
		padding: 5px;
	}

	h1 {
		margin: 0;
		text-align: left;
	}

	img {
		max-width: 7.5rem;
		margin-left: 3rem;
	}
	
	button {
    cursor: pointer; border: solid 1px transparent; border-radius: 5px; color: white; background: none;
}

button:hover {
    opacity: 0.75;
}
</style>
