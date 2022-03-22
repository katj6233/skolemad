<script>
	import Router, { location, link } from "svelte-spa-router";
	import Home from "./Home.svelte";
	import Footer from "./Footer.svelte";
	import Header from "./Header.svelte";
	import Login from "./Login.svelte";


	
</script>


<h1>Hej</h1>
<nav>
	<a href="/">Home</a>
	<a href="/#/login">Log in</a>
</nav>

<Router
routes={{
	'/#/': Home,
	'/login': Login,
}}
/>

<hr>{$location}



<Header></Header>


<main>
	
</main>

<Footer></Footer>



<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	/* h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	} */

     
	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>