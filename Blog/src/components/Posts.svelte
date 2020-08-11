<style lang="scss">
	aside{
		height: 90vh;
	}	
	.post{
		i{
			float: right;
		}
	}

	@media (max-width: 600px) {
		aside{
			position: absolute;
			z-index: -1;
		}
		
	}

</style>
<script></script>
<aside id="Posts-List" class="col s3 13 z-depth-1">
	<h5>Posts</h5>
	<hr>
	<ul>
	 	<li class="post">
			<b>Lorem Ipsum </b>
			<i>22-08</i>
			<p class="my-0">some thing that i cann not explain any more</p>
	 	</li>
	 </ul>
</aside>