<script>
    export let type;
</script>

<button class={type}><slot/></button>

<style>

    button {
        border-radius: 6px;
        padding: 0.2rem;
        width: fit-content;
        border: none;
        box-shadow: 2px 4px var(--default-button-color);
    }

    button:hover {
        background-color: var(--secondary-button-color);
    }
    
    .primary {
        background-color: var(--primary-button-color);
    }

    .secondary {
        background-color: var(--secondary-button-color);
    }
</style>