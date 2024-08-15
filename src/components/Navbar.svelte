<script lang="ts">
    import "../app.css";
  import Typewriter, { loop } from 'svelte-typewriter';


    

</script>



<main>
    <div class="border border-4 mx-[25%] my-3 py-5 rounded-2xl shadow-xl">
        
        <button class="ml-10">Home</button>
        <div class="mx-auto text-indigo-950" >
            <Typewriter mode=loopOnce>
                <h1>Hi!</h1>
                <h1>My name is Connor Cochran.</h1>
                <h1>I program.</h1>
                <h1>I am currently a student at The Ohio State University.</h1>
                <h1>I study Computer & Information Science.</h1>
                <h1>Connor M. Cochran</h1>
            </Typewriter>


            

        </div>
        <div class="space-x-10 mr-10">
        <button>Portfolio</button>
        <button>About</button>
        </div>

    </div>
</main>