<script>
	export let name;
</script>

<main>
	<div class="header">
		<h1>
			{name}
		</h1>
			<p>7th Grade Student | Learning CS </p>
			<a href="https://github.com/abhinavpentyala"
				><i class="fa fa-github fa-3x" aria-hidden="true"></i>
			
			</a>
			<a href="mailto:abhinav.pentyala@gmail.com"><i class="fa fa-envelope fa-3x" aria-hidden="true"></i>
			</a>
	</div>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		background-color: #232425;
	}

	h1 {
		color: #a9a9b3;
		font-size: 5em;
		font-weight: 100;
		text-align: center;
		margin: 1rem;
		font-family: 'Roboto', sans-serif;
	}

	.header {
		height: 100vh;
		margin-top: 20vh;
	}

	p {
		display: block;
		font-size:xx-large;
		color:#a9a9b3;
		font-weight:500;
		font-family: 'Montserrat', sans-serif;	
	}

	i {
		color:#a9a9b3;
		size:1000em
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>
