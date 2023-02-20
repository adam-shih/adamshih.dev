<script>
	import { onMount } from 'svelte';
	import init from './out/falling-sand.js';
	onMount(() => {
		init();
	});
</script>

<p class="text-center">Falling Sand Simulation</p>
<div class="flex">
	<canvas id="bevy-canvas" />
	<!-- <div class="flex-col">
		<p>Controls:</p>
		<p>[LeftClick] Place element</p>
		<p>[1] Sand</p>
		<p>[2] Water</p>
		<p>[3] Stone</p>
		<p>[4] Air (Eraser)</p>
	</div> -->
</div>

<style>
	.flex {
		display: flex;
		gap: 2rem;
		flex-wrap: wrap;
		justify-content: center;
	}

	.text-center {
		text-align: center;
	}

	.flex-col {
		display: flex;
		flex-direction: column;
	}

	.flex-col > p {
		margin: 0.5rem;
	}
</style>
