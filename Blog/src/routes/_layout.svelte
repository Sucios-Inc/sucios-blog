<script>
	import Nav from '../components/Nav.svelte'

	export let segment
</script>

<Nav {segment} />

<main class="row col s12 mx-0 px-0">
	<Posts />
	<slot />
</main>

<style lang="scss" global>
	@import 'styles/general';
	@import 'styles/materialize/sass/materialize';
	main {
		/*padding: 2em;*/
		color: white;
	}
</style>