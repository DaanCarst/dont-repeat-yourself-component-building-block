<script>
    import '../global.css';
    import header from '$lib/header.svelte';
</script>

<header {header} />

<main>
	<slot />
</main>
