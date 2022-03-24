<script>
    import Router, { location, link } from "svelte-spa-router";
    import Stefan from "../Pages/Stefan.svelte"
    import Button from "../Components/Button.svelte";
    
</script>


<section>

    <div class="forside_flex">

    <h1>Velkommen!</h1>

    <div class="formular">
    <h2>FORÆLDRE</h2>
    <input type="text" name="brugernavn" placeholder="Brugernavn" required>
    <input type="text" name="kodeord" placeholder="Kodeord" required>
    <div>
        <button class="btn1" type="secondary"><a class="font" href="/#/Stefan">Log in</a></button>
    </div>
    <div class="glemt">
        <a href="/#/">Glemt adgangskode?</a>
    </div>
    <hr>
    <div>
        <button class="btn2">Opret konto</button>
    </div>
   
</div>


<div class="center">
<Button type="primary">Skal du <strong>modtage</strong> mad?</Button>

<Button type="primary">Skal du <strong>levere</strong> mad?</Button> 

</div>

</div>

</section>

            

<Router
routes={{
	
	'/Stefan': Stefan,
}}
/>


<style>

hr {
    border: 0.1px grey solid;
    margin-block: 0.5rem;
}
.center {
	display: flex;
	justify-content: space-evenly;
    
    margin-top: 1.3rem;
    
}
    .formular {
        background-color: var(--background-login-color);
        width: 25rem;
        padding: 3.5rem;
        border-radius: 1rem;
        margin-top: 3rem;
        box-shadow: 0 8px 10px -1px rgb(0 0 0 / 0.1), 0 2px 4px -2px rgb(0 0 0 / 0.1);
    }

     h1, .glemt, h2 {
        text-align: center;
    }

    h2 {
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
        box-shadow: 0 8px 10px -1px rgb(0 0 0 / 0.1), 0 2px 4px -2px rgb(0 0 0 / 0.1);

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
        box-shadow: 0 8px 10px -1px rgb(0 0 0 / 0.1), 0 2px 4px -2px rgb(0 0 0 / 0.1);
}

.btn1 {
    background-color: var(--secondary-button-color);
}

.btn1:hover {
    background-color: var(--primary-button-color);
    text-decoration: underline;
}

.btn2 {
    background-color: var(--primary-button-color);
}

.btn2:hover{
    background-color: var(--secondary-button-color);
    text-decoration: underline;
}

.font {
    font-family: var(--heading);
    text-decoration: none;
}

button {
    cursor: pointer;
}

.glemt a:hover {
color: blue;
}



</style>