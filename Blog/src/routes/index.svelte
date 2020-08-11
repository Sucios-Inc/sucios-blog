<script context="module" lang="ts" >
	export async function preload(page, session) {
		console.log('preload!', page, session)
	}
</script>

<script lang="ts">
	import Posts from '@app/components/Posts.svelte'

	// import Counter from '@app/components/Counter.svelte'
</script>

<svelte:head>
	<title>Dirty Blog</title>
</svelte:head>

<template>
	<Posts />
	<section class="col s12 m9 19">
		<figure>
			<img src="" alt="">
			<figcaption></figcaption>
		</figure>
		<h3>Some new post</h3>
		<article>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Praesentium non, et cupiditate cum, iure ipsam facere dignissimos totam nam vitae, tempore eaque reprehenderit provident architecto deleniti facilis minima libero maxime. </article>
		<footer><i>date</i></footer>
	</section>
</template>


<style lang="scss">

</style>
