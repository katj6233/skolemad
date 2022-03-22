<script>
    import Router, { location, link } from "svelte-spa-router";
    import Stefan from "../Pages/Stefan.svelte"
    import Button from "../Components/Button.svelte";
    
</script>

<h1>Velkommen!</h1>

<section>

    <div class="formular">
    <h3>FORÆLDRE</h3>
    <input type="text" name="brugernavn" placeholder="Brugernavn" required>
    <input type="text" name="kodeord" placeholder="Kodeord" required>
    <div>
        <button class="btn1" type="secondary"><a href="/#/Stefan">Log in</a></button>
    </div>
    <hr>
    <div>
        <button class="btn2">Opret konto</button>
    </div>
    <div class="glemt">
        <a href="/#/">Glemt adgangskode?</a>
    </div>
</div>



<Button type="primary">Skal du <strong>modtage</strong> mad?</Button>

<Button type="primary">Skal du <strong>levere</strong> mad?</Button> 

</section>

            

<Router
routes={{
	
	'/Stefan': Stefan,
}}
/>


<style>

    .formular {
        background-color: var(--background-login-color);
        width: 25rem;
        padding: 2rem;
        border-radius: 1rem;
        
    }

    h1, .glemt, h3 {
        text-align: center;
    }

    h3 {
        margin-bottom: 1rem;
    }

    a {
        background-color: none;
    }
    input[type=text] {
        width: 100%; 
        padding: 12px;  
        border: none; 
        border-radius: 4px; 
        box-sizing: border-box; 
        margin-top: 6px; 
        margin-bottom: 16px; 
        resize: vertical;
        background-color: var(--default-input-color); 
}

 .btn2, .btn1 {
    width: 100%; 
        padding: 12px;  
        border: none; 
        border-radius: 4px; 
        box-sizing: border-box; 
        margin-top: 6px; 
        margin-bottom: 16px; 
        resize: vertical; 
}

.btn1 {
    background-color: var(--secondary-button-color);
}

.btn1:hover {
    background-color: var(--primary-button-color);
}

.btn2 {
    background-color: var(--primary-button-color);
}

.btn2:hover{
    background-color: var(--secondary-button-color);
}



</style>