<script>
	import Router from "svelte-spa-router";

	import Home from "./pages/home.svelte";
	let routes = {
		"/": Home,
	};
</script>

<div id="root">
	<Router {routes} />
</div>

<style>

	:root {
		background-color: black;
		color: white;
		font-family: "Phantom Sans";
	}

	@font-face {
		font-family: "Phantom Sans";
		src:
			url("https://assets.hackclub.com/fonts/Phantom_Sans_0.7/Regular.woff")
				format("woff"),
			url("https://assets.hackclub.com/fonts/Phantom_Sans_0.7/Regular.woff2")
				format("woff2");
		font-weight: normal;
		font-style: normal;
		font-display: swap;
	}

	#root {
		height: 100%;
		display: flex;
		flex-direction: column;
		margin: 0;
	}
</style>
