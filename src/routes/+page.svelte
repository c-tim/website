<script>
	import Home from './home.svelte';
	import Navbar from './navbar.svelte';
</script>

<main class="html">
	<div class="centered">
		<div class="centered framed">
			<h2 class="centered">Hi, Welcome to my website !</h2>
			<div>
				I'm a french student in computer science, currently studying game development at Telecom
				Sudparis. <br>I am currently looking for an internship at the end of my engineering studies. My
				resume is avalaible in the menu.<br>
				
				
				<p>
					Also check out my project on <a href="./my-projects"
						>this page</a
					>.
				</p>
			</div>

			<div class="centered underlined">
				<h2>Note on this website</h2>
			</div>
		</div>
	</div>
</main>

<style>
	@import './layout.css';

	.html {
		margin: 0;
		width: 100%;
		/* color:var(--primary-bg-color);*/
		background-color: gray;
		height: 100%;
	}
</style>
