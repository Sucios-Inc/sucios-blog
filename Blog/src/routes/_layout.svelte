<script>
	import Nav from '../components/Nav.svelte'

	export let segment
</script>

<Nav {segment} />

<main class="row">
	<slot />
</main>

<style lang="scss" global>
	@import 'styles/general';
	@import 'styles/materialize/sass/materialize';
	main {
		position: relative;
		background-color: white;
		padding: 2em;
		margin: 0 auto;
		box-sizing: border-box;
	}
</style>