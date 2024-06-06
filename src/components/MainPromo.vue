<template>
  <div class="bg-black flex flex-wrap">
    <div class="w-full sm:w-8/12 mb-10">
      <div class="container mx-auto h-full sm:p-10">
        <nav class="flex px-4 justify-between items-center">
          <div class="text-4xl font-bold text-white">
            ZipApi<span class="text-green-700">.</span>
          </div>
          <div>
            <img src="https://image.flaticon.com/icons/svg/497/497348.svg" alt="" class="w-8">
          </div>
        </nav>
        <header class="container px-4 lg:flex mt-10 items-center h-full lg:mt-0">
          <div class="w-full">
            <h1 class="text-4xl lg:text-6xl font-bold text-white">Принт на <span class="text-green-700">ЗИП</span> пакеты</h1>
            <div class="w-20 h-2 bg-green-700 my-4"></div>
            <p class="text-xl mb-10 text-white">Персонализированные ЗИП пакеты с вашим логотипом и дизайном. Идеально подходят для маркетинговых мероприятий и рекламных акций</p>
            
            <button class="bg-white text-black text-2xl font-medium px-4 py-2 rounded-full shadow">Заказать сейчас</button>
          </div>
        </header>
      </div>
    </div>
    <img :src="imageSrc" alt="Promo Image" class="w-full h-48 object-cover sm:h-screen sm:w-4/12">
  </div>
</template>

<script>
import promoImage from '@/assets/zip-package.webp';

export default {
  name: 'MainPromo',
  data() {
    return {
      imageSrc: promoImage,
    };
  },
};
</script>

<style scoped>
/* Дополнительные стили (если нужны) */
</style>
