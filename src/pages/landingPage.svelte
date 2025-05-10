<div id="landingPage">
	<div id="wrap">
		<div>
			<h1>Welcome to Hack Club</h1>
			<h3>
				A awesome community of 5,000+ teen hackers hackers from around
				the world who code together!
			</h3>
			<button> <span>Join Now! </span></button>
		</div>
		<div id="badge">⇊ Or scroll down to learn more! ⇊</div>
	</div>
</div>

<style>
	#landingPage {
		min-height: 100vh;
		height: 100vw;
		max-height: 100vh;
		width: 100%;
		background-image: url("https://user-images.githubusercontent.com/39828164/258882277-368eac86-3c39-4842-be2c-1436a6db6f07.png");
		background-size: cover;
		background-position: center;
	}

	#wrap {
		background-color: #000000d3;
		height: 100%;
		display: grid;
		place-items: center;
	}

	h1 {
		font-size: 100px;
		margin: 0;
	}
	h3 {
		font-size: 30px;
		margin: 0;
	}
	button {
		background-color: #052900;
		color: white;
		border: none;
		padding: 10px 20px;
		font-size: 20px;
		cursor: pointer;
		border-radius: 5px;
		border: none;
		border-radius: 12px;
		padding: 0;
		cursor: pointer;
		margin-top: 20px;
		span {
			display: block;
			padding: 12px 42px;
			border-radius: 12px;
			font-size: 1.25rem;
			background-color: #0b5e00;
			color: white;
			transform: translateY(-8px);
			transition: all 0.2s ease-in-out;
		}
	}
	button:hover span {
		transform: translateY(-12px);
	}
	button:active span {
		transform: translateY(-4px);
	}

	#badge {
		position: absolute;
		bottom: 10px;
		background-color: #042200;
		color: white;
		padding: 5px 10px;
		font-size: 15px;
		border-radius: 5px;
		cursor: pointer;
	}
</style>
