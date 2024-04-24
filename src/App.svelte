
<main>
	<h1>Svelte!</h1>
	<p>Svelte is a JavaScript framework that is primarily used to create applications.</p>
	<p>This is an example of a Svelte page.</p>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	p {
		font-size: 1.2em;
		color: #333; 
		padding: 0.5em 0; 
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>
