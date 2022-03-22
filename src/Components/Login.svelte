<script>
    import Router, { location, link } from "svelte-spa-router";
    import Stefan from "../Stefan.svelte"
</script>

<Router
routes={{
	
	'/Stefan': Stefan,
}}
/>


<section>
    <h3>FORÆLFRE</h3>
    <div>
        Brugernavn
    </div>
    <div>
        Kodeord
    </div>
    <div>
        <button><a href="/#/Stefan">Log in</a></button>
    </div>
    <div>
        Opret Konto
    </div>
</section>