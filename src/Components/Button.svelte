<script>
    export let type;
</script>

<button class={type}><slot/></button>

<style>

    button {
        border-radius: 6px;
        padding-block: clamp(0.7rem, 0.6399999999999999rem + 0.30000000000000004vw, 1rem);
        padding-inline: clamp(1rem, 0.92rem + 0.3999999999999999vw, 1.4rem);
        width: fit-content;
        border: none;
        box-shadow: 0 8px 10px -1px rgb(0 0 0 / 0.1), 0 2px 4px -2px rgb(0 0 0 / 0.1);
        font-size: clamp(0.7rem, 0.6599999999999999rem + 0.2000000000000001vw, 0.9rem);
        font-family: var(--heading);
        cursor: pointer;
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