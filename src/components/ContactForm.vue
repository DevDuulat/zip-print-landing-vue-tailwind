<template>
  <div class="contact-form bg-black py-16">
    <div class="max-w-7xl mx-auto">
      <div class="grid grid-cols-1 gap-4 lg:grid-cols-2 lg:gap-8">
        <div class="">
          <h2 class="text-5xl text-white font-bold mb-7">Оставьте заявку</h2>
          <form class="ml-auo space-y-4">

            <label
                for="UserName"
                class="relative text-white block overflow-hidden border-b border-gray-200 bg-transparent pt-3 focus-within:border-blue-600"
            >
              <input
                  type="email"
                  id="UserName"
                  placeholder="Name"
                  class="peer h-8 w-full border-none bg-transparent p-0 placeholder-transparent focus:border-transparent focus:outline-none focus:ring-0 sm:text-sm"
              />

              <span
                  class="absolute text-white  start-0 top-2 -translate-y-1/2 text-xs transition-all peer-placeholder-shown:top-1/2 peer-placeholder-shown:text-sm peer-focus:top-2 peer-focus:text-xs"
              >
    Имя
  </span>
            </label>
            <label
                for="UserEmail"
                class="relative text-white block overflow-hidden border-b border-gray-200 bg-transparent pt-3 focus-within:border-blue-600"
            >
              <input
                  type="email"
                  id="UserEmail"
                  placeholder="Emails"
                  class="peer h-8 w-full border-none bg-transparent p-0 placeholder-transparent focus:border-transparent focus:outline-none focus:ring-0 sm:text-sm"
              />

              <span
                  class="absolute text-white  start-0 top-2 -translate-y-1/2 text-xs transition-all peer-placeholder-shown:top-1/2 peer-placeholder-shown:text-sm peer-focus:top-2 peer-focus:text-xs"
              >
    Email
  </span>
            </label>

            <label
                for="UserEmail"
                class="relative text-white block overflow-hidden border-b border-gray-200 bg-transparent pt-3 focus-within:border-blue-600"
            >
              <textarea
                  type="email"
                  id="UserEmail"
                  placeholder="Emails"
                  rows="6"
                  class="peer h-8 w-full border-none bg-transparent p-0 placeholder-transparent focus:border-transparent focus:outline-none focus:ring-0 sm:text-sm"
              />

              <span
                  class="absolute text-white  start-0 top-2 -translate-y-1/2 text-xs transition-all peer-placeholder-shown:top-1/2 peer-placeholder-shown:text-sm peer-focus:top-2 peer-focus:text-xs"
              >
    Сообщение
  </span>
            </label>

            <button type='button'
                    class="inline-block rounded border border-white bg-black px-12 py-3 text-sm font-medium text-white hover:bg-white hover:text-black focus:outline-none focus:ring active:text-indigo-500">Отправить</button>
          </form>
        </div>
        <div class="flex items-center justify-center">
          <img class="rounded-lg object-cover" width="1340" height="1200" src="https://placehold.co/600x400" alt="Пример печати на ЗИП пакетах">
        </div>

      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'ContactForm'
}
</script>