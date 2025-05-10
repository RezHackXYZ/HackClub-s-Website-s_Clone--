<script>
	import LandingPage from "./landingPage.svelte";
	import Benefits from "./Benefits/Benefits.svelte";
</script>

<div id="root">
	<LandingPage />
	<Benefits />
</div>

<style>
	#root {
		display: grid;
		place-items: center;
		height: 100%;
	}
</style>
