<div id="projects">
	<article>
		<header>Forum Application</header>
		<body>
			<p>
				<!-- <a href="https://forum.adamshih.dev">Live Demo</a>
				&#x2022; -->
				<a href="https://github.com/adam-shih/forum">Source</a>
			</p>
			<p>
				A fullstack forum application inspired by websites like Reddit, Hacker News, Lobste.rs, etc.
			</p>
			<p>
				REST API built using Rust and the Axum framework alongside a PostgreSQL database. Deployed
				to my home server on a Raspberry Pi.
			</p>
			<p>
				Frontend built using JavaScript with SvelteKit. Deployed with Vercel serverless functions.
			</p>
		</body>
	</article>

	<article>
		<header>Voxel Engine</header>
		<body>
			<p>
				<a href="https://github.com/adam-shih/voxel-engine">Source</a>
			</p>
			<p>
				A voxel engine written in Rust using the <a href="https://bevyengine.org"
					>Bevy Game Engine</a
				>.
			</p>
			<p>Features include dynamic chunk loading/unloading and procedural terrain generation.</p>
			<p>Currently working to implement optimized meshing algorithms, and more block types.</p>
		</body>
	</article>

	<article>
		<header>Falling Sand Simulation</header>
		<body>
			<p>
				<a href="/projects/falling-sand">Demo</a>
				&#x2022;
				<a href="https://github.com/adam-shih/falling-sand">Source</a>
			</p>
			<p>A cellular automata to simulate various elements' physics and interactions.</p>
			<p>
				Written in Rust and built with the {' '}
				<a href="https://bevyengine.org">Bevy Game Engine</a>. Compiled into WebAssembly to run in
				the browser!
			</p>
		</body>
	</article>
</div>

<style>
	#projects {
		display: flex;
		flex-direction: column;
		gap: 2rem;
	}

	article {
		margin: 0;
	}
</style>
