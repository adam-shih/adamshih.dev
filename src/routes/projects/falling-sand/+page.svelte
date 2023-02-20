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
</style>
