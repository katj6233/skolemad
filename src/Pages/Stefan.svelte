<script>
    import Button from "../Components/Button.svelte"
</script>

<section>
    <div class="img_stefan">
        <img src="../img/groen.png" alt="Billede af noget grønt">
    </div>
    <div class="boks_wrapper">
        <div class="boks"></div>
        <h1>Velkommen Stefan!</h1>
        <p>Her kan du bestille skolemad til dine børn og sikre dem en hverdag med god kost og masser energi!</p>
    </div>
</section>

<section>
    <h2>Se her et overblik over bestilt skolemad til dit barn.
        For bestilling, tryk på knappen Bestil mad. </h2>
    <Button type="primary">Mikka</Button>
    <Button type="primary">Felix</Button>

    <div>
        <h3>Mad bestilt til xx</h3>

    </div>
    <a href="/#/">For at afbestille klik her</a>
</section>


<style>

    .img_stefan {
        width: auto;
        height: auto;
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

    .boks {
        background-color: red;
        width: 20rem;
        height: 10rem;
    }

}
</style>