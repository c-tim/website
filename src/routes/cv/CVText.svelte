<script>
  import Navbar from '../navbar.svelte'; 
  let value = $props();
</script>

<h1>{value.name}</h1>  
<p>{value.content}</p>

