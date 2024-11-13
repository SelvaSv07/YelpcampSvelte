<script>
	import '../app.css';
    import Header from './Header.svelte';
    import '@fontsource-variable/outfit'

	let { children } = $props();
</script>

<main class="w-full max-w-screen-xl px-4 md:px-0">
    <Header/>

    {@render children()}
</main>

<style>
    main {
        font-family: "Outfit Variable", sans-serif;
    }
</style>
