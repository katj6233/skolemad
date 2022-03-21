<script>
	import Footer from "./Footer.svelte"
	import Header from "./Header.svelte"

	export let name;
</script>

<body>
	

<Header></Header>


<main>
	<h1>Hej Rebecca {name}!</h1>
	<p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
</main>

<Footer></Footer>
</body>


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

     body {
		 background-image: url("../img/baggrund.jpg");
		 width: 100vw;
		 min-height: 100vh;
		 background-size: cover;
		 margin: 0rem;

	 }
	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>