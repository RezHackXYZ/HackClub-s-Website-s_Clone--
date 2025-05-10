<script>
	import FreeStuff from "./FreeStuff.svelte";
	import Hackathons from "./Hackathons.svelte";
	import Ysws from "./ysws.svelte";
</script>

<div id="root"><div id="items"><Ysws /><Hackathons /><FreeStuff /></div></div>

<style>
	#root {
		height: 100vh;
	}

	#items {
		display: grid;
		grid-template-columns: repeat(3, minmax(300px, 1fr));
		gap: 20px;
		padding: 40px;
		max-width: 100%;
		justify-items: center;
	}
</style>
