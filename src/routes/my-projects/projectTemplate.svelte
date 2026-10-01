<script>
	import Navbar from '../navbar.svelte';
	let { value } = $props();
</script>

<style>
    .s-btn{
        margin-top: 40px;
  text-align: center;
  background:transparent;
  color:#e5e7eb;
  border-radius:80px;
  border:3px solid #1e293b;
  transition:.3s;
  padding: 10px 10px 10px 10px;
}
.s-btn:hover{
  background:transparent;
  box-shadow:0 0 0 2px #2563eb;
}


.remove-bg{
    background: transparent;
}

.title-project{
    font-size: 20px;
}



</style>

<div class="s-btn">
    
    <a href={value.url} class = "remove-bg">
    <h1 class = "remove-bg title-project">{value.title}</h1>
    <p class = "remove-bg">{value.content}</p>
    </a>
    
</div>