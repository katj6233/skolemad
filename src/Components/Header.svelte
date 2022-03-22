<script>	
    import Router, { location, link } from "svelte-spa-router";
	import Home from "../Pages/Home.svelte";
	import Login from "./Login.svelte";
    import Stefan from "../Stefan.svelte";

</script>
<section id="navigation">

    <div class="logo">
        <img  src="./img/logo.png" alt="">
    </div>  
    <nav>
        <ul id="links">
            <li><a href="/">Home</a></li>
            <li><a href="/#/">Om os</a></li>
            <li><a href="/#/">Kontakt</a></li>
        </ul>
    </nav>

</section>
<Router
routes={{
	'/#/': Home,
	'/login': Login,
    '/Stefan': Stefan,
}}
/>


<style>
    
    /* MENU */

    
    .logo img {
        width: 10rem;
    }    
    #navigation {
        display: flex;
        align-items: center;
        background-color: rgba(255, 255, 255, 0.295);
        justify-content: space-between;
        padding-left: 5rem;
        padding-right: 5rem;
        padding-top: 1.5rem;
        padding-bottom: 1.5rem;
        
    }
    
    #links {
        display: flex;
        gap: 4rem;
        list-style: none;
        
    }

    li a {
        text-decoration: none;
    }



    /* #navigation2 {
        display: flex;
        align-items: center;
        
    } */

</style>