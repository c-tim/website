<script>
	import Home from './home.svelte';
	import Navbar from './navbar.svelte';
</script>

<main class="html">
	<div>
		<p>
			Hi, I'm Timothée Cuq, a french student in computer science in Telecom SudParis. I am currently
			studying game development, but I also did projects in data science, web developement. During
			my free time, I play music, go on hikes and developp projects. You can check them out on <a href="./my-projects">this
			page</a>.
		</p>
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
