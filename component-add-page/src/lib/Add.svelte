<section class="content-container">
    <section class="tip-container">
        <p class="tip">Tip</p>
        <p>Voeg een bestaande url toe van de website van een partner!</p>
    </section>

    <section class="form-container">
        <p>Voeg een pagina titel toe</p>
        <input type="text">

        <p>Voeg een Partner URL toe</p>
        <input type="text">

        <button>Project Toevoegen</button>
    </section>
</section>

<style>
	.content-container {
        width: 100%;
        display: flex;
        flex-direction: row;
        justify-content: flex-start;
        align-items: flex-start;
    }

    .tip-container, .form-container {
        
        background-color: var(--c-container);
        margin: .5em;
        border-radius: 5px;
        display: flex;
        flex-direction: column;
        justify-content: flex-start;
        align-items: flex-start;
        padding: 1.2em;

    }

    .form-container {
        width: 100%;
        line-height: 2em;
    }

    .tip {
        color: var(--c-orange);
        line-height: 1.5em;
    }
</style>