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
    font-size: 2rem;
    
}



@font-face {
  font-family: "Myria";
  src: url(font/MYRIADAS.woff2) format("woff2");
}

:root {
--logo: "Myria", sans-serif;
}
ul {
    display: flex;
    justify-content: center;
    padding-top: 1.5rem;
    padding-bottom: 1rem;
}

ul li a {
    font-size: 1.2rem;
}
#navigation {
    padding: 1rem;
    background-color: rgba(255, 255, 255, 0.295);
    box-shadow: 0 8px 10px -1px rgb(0 0 0 / 0.1), 0 2px 4px -2px rgb(0 0 0 / 0.1);
}


    
    
      
   
    #links {
        display: flex;
        gap: 4rem;
        list-style: none;
        
    }

    li a {
        text-decoration: none;
    }


    /* MEDIAQUERY 640 px */
    @media screen and (min-width: 640px) {
        ul {
    
    padding-top: 2rem;
   
    }   
    }


    /* MEDIAQUERY 768 px */

    @media screen and (min-width: 768px) {

        #navigation {
        display: flex;
        align-items: center;
        justify-content: space-between;
        padding-left: 3rem;
        padding-right: 3rem;
        padding-top: 1.5rem;
        padding-bottom: 1.5rem;
        
    }

    ul {
    padding-top: 0;
    padding-bottom: 0;
    } 

    .logo {
        padding-top: 0;
    }

    }


    /* MEDIAQUERY 1024 px */
    @media screen and (min-width: 1024px) {

        .logo a {
    font-size: 2.6rem;
    
    }

    ul li a {
    font-size: 1.3rem;
    }

    }


    /* MEDIAQUERY 1280 px */
    @media screen and (min-width: 1280px) {


        #navigation {
       
        padding-left: 4rem;
        padding-right: 4rem;
    

    }
}

/* MEDIAQUERY 1536 px */
@media screen and (min-width: 1536px) {

    #navigation {
        padding: 1.8rem;
        padding-left: 5rem;
        padding-right: 5rem;
    
    }

    #links {
        gap: 6rem;
    }

}





</style>