<script lang="ts">
	import './layout.css';
	import favicon from '$lib/assets/favicon.svg';
	import profilePic from '$lib/assets/pic_bgremoved.png';

	let { children } = $props();
</script>

<style>



</style>

<svelte:head><link rel="icon" href={favicon} /></svelte:head>
{@render children()}
<nav class="sidenav ">
	<!-- svelte-ignore a11y_img_redundant_alt -->
    <a href="/"  >Home</a>
    <a href="/cv" >Resume</a>
    <a href="/my-projects" >Projects</a>
	<a href="/contact" >About</a>

</nav>
