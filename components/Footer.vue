<template>
  <footer class="text-white body-font Bg-SecondaryColor">
  <div class="container px-5 py-8 mx-auto flex items-center sm:flex-row flex-col">
    <a class="flex title-font font-medium items-center md:justify-start justify-center text-gray-100">
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-10 h-10 text-white p-2 Bg-PrimaryColor rounded-full" viewBox="0 0 24 24">
        <path d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5"></path>
      </svg>
      <span class="ml-3 text-xl">Web Developer</span>
    </a>
    <p class="text-sm text-gray-300 sm:ml-4 sm:pl-4 sm:border-l-2 sm:border-gray-200 sm:py-2 sm:mt-0 mt-4">© 2022 Pavel Polistovskiy —
      <a href="https://github.com/poliweb" class="text-gray-400 ml-1" rel="noopener noreferrer" target="_blank">@PoliWeb</a>
    </p>
    <span class="inline-flex sm:ml-auto sm:mt-0 mt-4 justify-center sm:justify-start">
      <SocIcons/>
    </span>
  </div>
</footer>
</template>

<script>
export default {};
</script>

<style>
.Bg-PrimaryColor {
  background: #2c97dd;
}

.Bg-SecondaryColor {
  background: #0e5d90;
}
</style>
