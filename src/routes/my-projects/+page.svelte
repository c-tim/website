


<script>
	import { text } from '@sveltejs/kit';
  import Navbar from '../navbar.svelte'; 
  //import project from ./ProjectTemplate.sv
	import ProjectTemplate from './projectTemplate.svelte';

  let descriptions = {
    itch:"Here's the link to my Itch page, where I have all the games I made during my personnal time or for gameJams",
    logicMath:"A personnal project aiming to understands better the functionning of a compiler and used to compile mathematicals expressions written in a human-readable format.",
    ecostream:"A small chrome plugin that estimates the consumption of videos and proposes small features to decrease it. Help for an academic project of the author of the repository.",
    cppGame:"Small C++ game built without game engine, developped for a school project.",
    yasc:"Small game made to get used to the game engine Unreal Engine, developped for a school project. 3D models made with Blender and music made with Fl Studio."

     }
</script>


<main>
  
  <h1 class="title-page underlined">My Projects</h1>
  <hr>

  <ProjectTemplate  value={{title:"Itch.io games", content:descriptions.itch, url:"https://itch.io/profile/c-tim"}}/>
  
  <ProjectTemplate  value={{title:"Compiler of Math content", content:descriptions.logicMath, url:"https://codeberg.org/azurT/logicMath"}}/>

  <ProjectTemplate  value={{title:"Ecostream : small plugin to reduce Youtube video consumption", content:descriptions.ecostream, url:"https://github.com/sunaald/EcoStream_extension"}}/>

  <ProjectTemplate  value={{title:"C++ Game", content:descriptions.cppGame, url:"https://github.com/c-tim/cppGame"}}/>

  <ProjectTemplate  value={{title:"Unreal Engine Game", content:descriptions.yasc, url:"https://github.com/Helo1204/YASC"}}/>


</main>
