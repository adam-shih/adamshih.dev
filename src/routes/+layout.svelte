<script>
	import '@picocss/pico';
	import '@fontsource/jetbrains-mono';
	import Nav from '$lib/Nav.svelte';
	import Footer from '$lib/Footer.svelte';
	import '$lib/global.css';
</script>

<body id="layout" class="container">
	<Nav />
	<main>
		<slot />
	</main>
	<div id="footer">
		<Footer />
	</div>
</body>

<style>
	#layout {
		display: flex;
		flex-direction: column;
		min-height: 100vh;
	}

	#footer {
		margin-top: auto;
	}

	body {
		font-family: 'JetBrains Mono', monospace;
	}

	:global(h1, h2, h3, h4, h5, h6) {
		font-family: 'JetBrains Mono', monospace;
	}
</style>
