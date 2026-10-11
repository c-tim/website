<script>
	import CodeBergIcon from '$lib/assets/codeberg_logo.png';
	import GithubIcon from '$lib/assets/github_logo.png';
	import LinkedInIcon from '$lib/assets/linkedin_logo.jpg';
</script>

<style>

.line{
  
}

.imageIcon{
  display:inline;
  width: 300px;
  height: 300px;
}

</style>

<main>
	<h1 class="title-page underlined">Contacts</h1>

	<h2 class = "centered">Follow in my links</h2>

	<div class="centered">
		<div class="line">
			<a href="./">
				<img src={CodeBergIcon} class="imageIcon"  alt="Codeberg Icon" />
			</a>

			<a href="./">
				<img src={GithubIcon} class="imageIcon" alt="Github Icon" />
			</a>
			<a href="./">
				<img src={LinkedInIcon} class="imageIcon" alt="LinkedIn Icon" />
			</a>
		</div>
	</div>
</main>
