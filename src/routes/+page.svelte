<script lang="ts">
  import "../app.css";
  import Typewriter, { loop } from 'svelte-typewriter';
  import  {Splide, SplideSlide} from '@splidejs/svelte-splide';
  import '@splidejs/svelte-splide/css';  

</script>

<head>
    <title>Connor M. Cochran</title>
</head>


<div class="border border-4 my-3 mx-10 py-5 min-h-96 rounded-2xl shadow-xl">
  <div class="ml-10 my-auto text-4xl">
    <Typewriter mode=loopOnce cursor={false}>
                    <h1>Hi!</h1>
                    <h1>My name is Connor Cochran.</h1>
                    <h1>I program.</h1>
                    <h1>I am currently a student at The Ohio State University.</h1>
                    <h1>I study Computer & Information Science.</h1>
                    <h1>Connor M. Cochran</h1>
    </Typewriter>
</div>

<div class="absolute space-x-10 bottom-10 ml-8">
    <icon><a href="https://www.github.com/CoCochran" target="_blank"><img src="../../icons/github-mark.webp" alt="Github"></a></icon>
    <icon><a href="https://www.linkedin.com/in/connor-cochran-a69241251/" target="_blank"><img src="../../icons/in-black.webp" alt="LinkedIn"></a></icon>
    <icon><a href="https://leetcode.com/u/cocochran/" target="_blank"><img class="w-[40px] h-[40px]" src="../../icons/leetcode-black.webp" alt="Leetcode"></a></icon>
  </div>
</div>

<div class="justify-center">
<div class="shadow-xl rounded-xl">
  <Splide 
  options={
    {
      arrows: false,
      width: 800,
      pagination: true,
    }
  }
  class="">

    <SplideSlide>
      <img src="../../img/black_background_800x400.png" alt="Hi" class="rounded-2xl border border-8">
    </SplideSlide>

    <SplideSlide>
      <img src="../../img/black_background_800x400.png" alt="Hi" class="rounded-2xl border border-8">
    </SplideSlide>

    <SplideSlide>
      <img src="../../img/black_background_800x400.png" alt="Hi" class="rounded-2xl border border-8">
    </SplideSlide>

    <SplideSlide>
      <img src="../../img/black_background_800x400.png" alt="Hi" class="rounded-2xl border border-8">
    </SplideSlide>
    
    <SplideSlide>
      <img src="../../img/black_background_800x400.png" alt="Hi" class="rounded-2xl border border-8">
    </SplideSlide>
  </Splide>
</div>
</div>

<body class="">
    
</body>
