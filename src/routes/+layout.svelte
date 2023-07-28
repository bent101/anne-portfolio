<script>
	import "../app.css";
	import { dev } from "$app/environment";
	import { inject } from "@vercel/analytics";

	inject({ mode: dev ? "development" : "production" });
</script>

<svelte:head>
	<title>Anne Dyke Flute</title>
	<meta
		name="description"
		content="Anne Dyke performs and teaches piano and flute in the Raleigh area"
	/>
</svelte:head>

<slot />
