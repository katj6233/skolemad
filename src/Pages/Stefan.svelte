<script>
    import Button from "../Components/Button.svelte"
    import Tabel from "../Components/Tabel.svelte"
</script>

<section>
    <div class="img_stefan">
        <img src="../img/groen.png" alt="Billede af noget grønt">
    </div>
    <div class="boks_wrapper">
        
        <h1>Velkommen Stefan!</h1>
        <p>Her kan du bestille skolemad til dine børn og sikre dem en hverdag med god kost og masser energi!</p>
    </div>
</section>

<section class="section_2">
    <h2 class="under_o">Se her et overblik over bestilt skolemad til dit barn.</h2>
    <h3 class="under_o1">For bestilling, tryk på knappen Bestil mad. 
        Når bestillingen er udført, gå til kurv for betaling. 
         </h3>

    <div class="flex">
    
        <div class="place_a">
    <Button type="primary">Mikka</Button>
    <Button type="primary">Felix</Button>
</div>
    
    <div class="place_b">
        <Button type="primary">Bestil mad</Button>
    </div>
        </div>

    <div>
        <h3 class="underline">Mad bestilt til xx</h3>
        <Tabel></Tabel>
    </div>
    
</section>




<style>







    img {
        height: 300px;
        width: 390px;
        object-fit: cover;
        object-position: center center;
        z-index: -1;
    }

    section {
        display: grid;
        
    }

    h1 {
        margin-bottom: 1rem;
    }

    .img_stefan {
        grid-area: 1/1;
    }

    .boks_wrapper {
        grid-area: 1/1;
        place-self: center;
        margin-inline: 2rem;
        padding: 2rem;
        background-color: rgb(255, 255, 255, 70%);
        width: fit-content;
        height: fit-content;
        border-radius: 8px; 
        box-shadow: 0 8px 10px -1px rgb(0 0 0 / 0.1), 0 2px 4px -2px rgb(0 0 0 / 0.1);
    }

    .section_2 {
        margin: 2rem;
    }

    .under_o {
        font-weight: 600;
        margin-bottom: 0.5rem;
    }

    .under_o1 {
        font-weight: 400;
        margin-bottom: 1.5rem;
    }

    .flex {
        display: flex;
        margin-bottom: 2rem;
    }

    .flex {
        justify-content: space-between;
    }

    

    .underline {
        text-decoration: underline;
    }

   

   
    
    @media (min-width: 640px) {

    section {
        display: grid;
    }

    .img_stefan {
        grid-area: 1/1;
    }

    .boks_wrapper {
        grid-area: 1/1;
    }

    img {
        width: 640px;
    }
    h3 {
        margin-right: 10rem;
    }

    .section_2 {
        margin-inline: 4rem;
    }


}

@media (min-width: 768px) {
    img {
        width: 768px;
    }

    .under_o1 {
        margin-bottom: 3rem;
    }
    .boks_wrapper {
        margin-left: 6rem;
        margin-right: 14rem;
    }

    .section_2 {
        margin-inline: 6rem;
    }

    h3 {
        margin-right: 12rem;
    }

    
}

@media (min-width: 1024px) {
    img {
        width: 1024px;
    }

    .under_o1 {
        margin-bottom: 3rem;
    }
    .boks_wrapper {
        margin-left: 8rem;
        margin-right: 25rem;
    }

    .section_2 {
        margin-inline: 8rem;
    }

    
    h3 {
        margin-right: 25rem;
    }
}

@media (min-width: 1280px) {
    img {
        width: 1280px;
    }

    .under_o1 {
        margin-bottom: 4rem;
    }
    .boks_wrapper {
        margin-left: 10rem;
        margin-right: 30rem;
    }

    .section_2 {
        margin-inline: 10rem;
    }

    h3 {
        margin-right: 30rem;
    }
    
}

@media (min-width: 1536px) {
    img {
        width: 1536px;
        height: 450px;
    }

    .boks_wrapper {
        margin-left: 10rem;
        margin-right: 50rem;
    }

    .section_2 {
        margin-inline: 10rem;
    }

    h3 {
        margin-right: 45rem;
    }
    
}
</style>