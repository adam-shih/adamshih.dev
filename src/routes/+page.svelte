<script>
	import Chip from '$lib/Chip.svelte';

	const interests = [
		'Backend Development',
		'Embedded Systems',
		'Game Development',
		'Software Security',
		'Rust Programming Language'
	];
</script>

<header>
	<h1>Adam Shih</h1>
	<p>Software Engineer</p>
</header>

<div>
	<p>
		A passionate developer in pursuit of continuous learning, best practices, and personal
		improvement.
	</p>

	<div id="interests">
		<strong id="label">Technical Interests:</strong>
		<span id="chips">
			{#each interests as interest}
				<Chip text={interest} />
			{/each}
		</span>
	</div>
</div>

<style>
	header {
		margin-bottom: 3rem;
	}

	h1 {
		margin: 0;
	}

	#label {
		flex-shrink: 0;
		color: var(--secondary);
	}

	#interests {
		display: flex;
		flex-direction: column;
		gap: 1rem;
	}
</style>
