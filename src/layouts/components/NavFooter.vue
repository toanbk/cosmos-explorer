<template>
  <!-- footer -->
  <footer
    class="flex items-center h-12 mt-5 text-sm bg-gray-100 dark:bg-[#171d30] py-2 z-10 w-full"
  >
    <div class="flex flex-1">
      &copy;&nbsp;
      {{ new Date().getFullYear() }}&nbsp;
      Made With&nbsp;
      <img src="../../assets/images/heart.svg" />&nbsp;
      By&nbsp;
      <a
        class="link link-primary no-underline"
        href="https://cherryvalidator.us"
        target="_blank"
        rel="noopener noreferrer"
        >CherryValidator</a
      >
    </div>
    <div
      class="hidden md:!block"
    >
      <a
        class="link link-primary no-underline"
        href="https://github.com/toanbk"
        target="noopener noreferrer"
        >Github</a
      >
    </div>
  </footer>
</template>