<template>
 <div class="bg-white text-[#333] p-8 font-[sans-serif]">
      <div class="max-w-3xl mx-auto grid md:grid-cols-2 justify-center items-center max-md:text-center gap-4">
        <div>
          <h2 class="text-4xl md:text-5xl font-extrabold mb-6 md:!leading-[55px]">Try using our templates</h2>
          <p class="text-base mb-8">Upgrade to our premium plan and supercharge your experience. Don't miss out!</p>
          <button type="button"
            class="min-w-[160px] px-4 py-2 text-base tracking-wider font-semibold outline-none border border-[#333] hover:bg-[#222] hover:text-white transition-all duration-300">Try now</button>
        </div>
        <div class="md:text-right max-md:mt-12">
          <img src="https://readymadeui.com/photo.webp" alt="Premium Benefits" class="md:w-4/5 inline-block" />
        </div>
      </div>
    </div>
</template>

<script>
export default {
  name: 'CtaSection'
}
</script>