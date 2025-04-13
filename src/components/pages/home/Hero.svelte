<script>
  import { fade, scale } from "svelte/transition";
  const title = "I develop the best";
  const ctaText = "Learn More";
  const ctaLink = "about";
</script>

<section transition:fade class="relative flex items-center justify-center text-center py-16 text-white">
  <div class="max-w-2xl mx-auto">
    <h1  class="text-4xl font-bold mb-4">{title}</h1>    
    <div class="">
      <h2 class="text-black font-bold text-5xl bg-[#F8CE68] w-1/2 mx-auto py-2 my-6 relative">APPLICATION<span class="absolute -top-4 -right-10">
        <img src="https://res.cloudinary.com/dmnwzu0xb/image/upload/v1668313548/rylic-assets/images/boom_wy6xl6.svg" alt="" class="" style="translate: none; rotate: none; scale: none; transform: translate(0px, 0px);" />
      </span></h2> 
      
    </div>
    <p transition:scale class="text-lg mb-6">Focusing on <b>web</b> & <b>mobile</b> development, I’m dedicated to delivering scalable and robust solutions that drive business success.</p>
    <a href={ctaLink} class="inline-block px-6 py-3 text-white bg-red-500 rounded-lg hover:bg-red-600 transition">
      {ctaText}
    </a>
  </div>

</section>

<style>
  h2 {
    transform: rotate(-5deg);
  }
</style>
