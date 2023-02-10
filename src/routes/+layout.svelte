<script>
	import pico from '@picocss/pico';
</script>

<body class="container">
	<nav>
		<a href="/">/</a>
		<a href="/projects">Projects</a>
		<a href="/resume">Resume</a>
		<a href="/contact">Contact</a>
	</nav>

	<main>
		<slot />
	</main>

	<footer>&copy; Adam Shih 2023</footer>
</body>

<style>
	a {
		text-align: center;
	}

	nav {
		gap: 3rem;
		justify-content: center;
		margin-top: 1rem;
	}
</style>
