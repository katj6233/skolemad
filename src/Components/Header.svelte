<script>	
    import Router, { location, link } from "svelte-spa-router";
	import Home from "../Pages/Home.svelte";
	import Login from "../Components/Login.svelte";
    import Stefan from "../Pages/Stefan.svelte";

</script>
<section id="navigation">


    <div class="logo">

             <a href="/"><p>SkoleMad</p></a>

    </div>  
    <nav>
        <ul id="links">
            <li><a href="/#/">Om os</a></li>
            <li><a href="/#/">Kontakt</a></li>
        </ul>
    </nav>

</section>
<Router
routes={{
	'/': Home,
	'/login': Login,
    '/Stefan': Stefan,
}}
/>


<style>
    
    /* MENU */


.logo {
    display: flex;
    justify-content: center;
    padding-top: 1rem;
}

.logo a {
    text-decoration: none;
    font-family: 'Myria';
    
}



@font-face {
  font-family: "Myria";
  src: url(font/MYRIADAS.woff2) format("woff2");
}
ul {
    display: flex;
    justify-content: center;
    padding-top: 1.5rem;
    padding-bottom: 1rem;
}

#navigation {
    padding: 1rem;
}


    @media screen and (min-width: 640px) {
        
    }
    
      
    /* #navigation {
        display: flex;
        align-items: center;
        background-color: rgba(255, 255, 255, 0.295);
        justify-content: space-between;
        padding-left: 5rem;
        padding-right: 5rem;
        padding-top: 1.5rem;
        padding-bottom: 1.5rem;
        
    } */
    
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