<script>
	export let text;
</script>

<div id="chip">{text}</div>

<style>
	#chip {
		background: var(--secondary);
		display: inline-block;
		padding: 0.125rem 0.5rem;
		border-radius: var(--border-radius);
		margin-right: 0.5rem;
		margin-bottom: 0.5rem;
		color: white;
	}
</style>
