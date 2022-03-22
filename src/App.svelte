<script>
	import Router,{ location,link} from "svelte-spa-router"
	import Footer from "./Footer.svelte"
	import Header from "./Header.svelte"
	import Login from "./Login.svelte"

	
</script>

<nav>
	<a href="/#/login">Log in</a>
</nav>

<Router
routes={{
	'/login': Login
}}
></Router>
	

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