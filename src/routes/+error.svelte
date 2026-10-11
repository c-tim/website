<script lang="ts">
    import { page } from '$app/state';
</script>

<style>

    .error-title{
        font-size: 8rem;
        margin: auto;
    }

    .error-submessage{
        margin: auto;
        font-size: 2rem;
        padding-top: 0px;
    }

</style>

<div class= "centered">
    
    <h1 class = "error-title">{page.status} </h1>
    <h2 class="error-submessage">{page.error?.message}</h2>
    
    <p> return to <a href="./">home</a></p>
</div>