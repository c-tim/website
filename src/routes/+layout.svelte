<script lang="ts">
	import './layout.css';
	import favicon from '$lib/assets/favicon.svg';
	import profilePic from '$lib/assets/pic_bgremoved.png';

	let { children } = $props();
</script>

<svelte:head><link rel="icon" href={favicon} /></svelte:head>
{@render children()}
<nav class="sidenav">
	<!-- svelte-ignore a11y_img_redundant_alt -->
	<img src={profilePic} class="image" alt="Profile picture">
    <a href="/"  >Home</a>
    <a href="/cv" >Resume</a>
    <a href="/my-projects" >Projects</a>
	<a href="/about" >About</a>

</nav>
