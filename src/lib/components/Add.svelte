
<section class="content-container">
    <section class="tip-container">
        <p class="tip">Tip</p>
        <p>Voeg een bestaande url toe van de website van een partner!</p>
    </section>

    <section class="form-container">
        <p>Voeg een pagina titel toe</p>
        <input type="text" placeholder="Titel van pagina..."><br>

        <p>Voeg een Partner URL toe</p>
        <input type="text" placeholder="Link naar pagina..."><br>

        <button class="add-button">Project Toevoegen</button>
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

    .add-button {
        border: none;
        background-color: var(--c-modal-button);
        color: white;
        padding: .7em;
        cursor: pointer;
        text-decoration: none;
        transition: 0.3s;
        border-radius: 4px;
    }

    input[type=text], select {
        width: 100%;
        padding: 12px 20px;
        margin: 8px 0;
        display: inline-block;
        border: 1px solid #ccc;
        border-radius: 4px;
        box-sizing: border-box;
}

    .add-button:hover {
        opacity: 0.75;
    }

</style>