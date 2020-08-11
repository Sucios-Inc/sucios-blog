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
	<section class="col s9">
		<figure>
			<img src="" alt="">
			<figcaption></figcaption>
		</figure>
		<article></article>
		<footer></footer>
	</section>
</template>


<style lang="scss">

</style>
