<script>
	export let name;
</script>

<main>
	<h1>Hello {name}!</h1>
	<p>Post content and earn Bitcoin</p>
<form>
	<input type="email"/>
	<button type="submit">Subscribe</button>
</form>
	
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #0b82de;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>