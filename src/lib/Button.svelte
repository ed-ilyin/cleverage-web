<script>
	export let href;
</script>

<a {href} target="_blank"><slot /></a>

<style>
	a {
		text-decoration: none;
		color: white;
		background-color: #cde4;
		border-radius: 8px;
		padding: 8px;
		margin: 8px;
		font-size: xx-large;
	}
	a:hover {
		background-color: #cde7;
	}
</style>
