<template>
  <nav class="fixed w-full z-30 top-0 bg-white py-2">
    <div class="w-full container mx-auto flex flex-wrap items-center justify-between mt-0 py-2">
      <div class="pl-4 flex items-center">
        <!-- <img src="./assets/logo1.svg" alt="" /> -->
      </div>
      <div class="block lg:hidden pr-4">
        <button class="flex items-center p-1 text-orange-800 hover:text-gray-900" @click.prevent.stop="onToggleClick">
          <svg class="fill-current h-6 w-6" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
            <title>Menu</title>
            <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z" />
          </svg>
        </button>
      </div>

      <div
        class="
          w-full
          flex-grow
          lg:flex
          lg:items-center
          lg:w-auto
          lg:block
          mt-2
          lg:mt-0
          bg-white
          lg:bg-transparent
          text-black
          p-4
          lg:p-0
          z-20
        "
      >
        <ul class="list-reset lg:flex justify-start flex-1 items-center">
          <li class="mr-3">
            <a class="inline-block py-2 px-4 text-black font-bold no-underline" href="#">What's different</a>
          </li>
          <li class="mr-3">
            <a class="inline-block text-black no-underline hover:text-gray-800 hover:text-underline py-2 px-4" href="#"
              >Product</a
            >
          </li>
          <li class="mr-3">
            <a class="inline-block text-black no-underline hover:text-gray-800 hover:text-underline py-2 px-4" href="#"
              >Resources</a
            >
          </li>
        </ul>
        <button class="mx-auto lg:mx-0 font-bold mt-4 lg:mt-0 py-4 px-8 rounded shadow">Sign in</button>
        <button class="mx-auto lg:mx-0 font-bold rounded-full mt-4 lg:ml-4 lg:mt-0 py-4 px-8 shadow bg-blue">
          Get early access
        </button>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'Header',
}
</script>

<style scoped>
</style>

