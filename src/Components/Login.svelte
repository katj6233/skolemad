<script>
    import Router, { location, link } from "svelte-spa-router";
    import Stefan from "../Pages/Stefan.svelte"
    
</script>

<h1>Velkommen!</h1>

<section>
    <h3>FORÆLFRE</h3>
    <input type="text" name="brugernavn" placeholder="Brugernavn" required>
    <input type="text" name="kodeord" placeholder="Kodeord" required>
    <div>
        <button class="btn1"><a href="/#/Stefan">Log in</a></button>
    </div>
    <div>
        <button class="btn2">Opret konto</button>
    </div>
</section>


            

<Router
routes={{
	
	'/Stefan': Stefan,
}}
/>


<style>
    input[type=text] {
        width: 100%; 
        padding: 12px;  
        border: 1px solid #ccc; 
        border-radius: 4px; 
        box-sizing: border-box; 
        margin-top: 6px; 
        margin-bottom: 16px; 
        resize: vertical 
}

.bt1 {
    width: 100%; 
        padding: 12px;  
        border: 1px solid #ccc; 
        border-radius: 4px; 
        box-sizing: border-box; 
        margin-top: 6px; 
        margin-bottom: 16px; 
        resize: vertical; 
        
}



</style>