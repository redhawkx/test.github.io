<script>
	import Home from "./Home.svelte";
	import Contact from "./Contact.svelte";
	import Router from "svelte-spa-router";
</script>

<style global lang="postcss">
	@tailwind base;
	@tailwind components;
	@tailwind utilities;
</style>

<Router routes = {{
	'/': Home,
	'/contact': Contact
}} />