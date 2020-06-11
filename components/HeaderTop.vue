<template>
  <header class="text-gray-700 body-font">
    <div
      class="container flex flex-col flex-wrap items-center p-5 mx-auto md:flex-row"
    >
      <a
        class="flex items-center mb-4 font-medium text-gray-900 title-font md:mb-0"
      >
        <img src="~/assets/logo_sm.png" class="w-12" alt="" />
        <path
          d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5"
        ></path>
        <span class="ml-3 text-xl">Ed's Coding</span>
      </a>
      <nav
        class="flex flex-wrap items-center justify-center text-base md:ml-auto md:mr-auto"
      >
        <nuxt-link to="/" class="mr-5 hover:text-gray-900">Home</nuxt-link>
        <nuxt-link to="projects" class="mr-5 hover:text-gray-900"
          >Projects</nuxt-link
        >
        <nuxt-link to="skills" class="mr-5 hover:text-gray-900"
          >Skills</nuxt-link
        >
        <nuxt-link to="contact" class="mr-5 hover:text-gray-900"
          >Contact</nuxt-link
        >
      </nav>
      <button
        class="inline-flex items-center px-3 py-1 mt-4 text-base bg-gray-200 border-0 rounded focus:outline-none hover:bg-gray-300 md:mt-0"
      >
        Button
        <svg
          fill="none"
          stroke="currentColor"
          stroke-linecap="round"
          stroke-linejoin="round"
          stroke-width="2"
          class="w-4 h-4 ml-1"
          viewBox="0 0 24 24"
        >
          <path d="M5 12h14M12 5l7 7-7 7"></path>
        </svg>
      </button>
    </div>
  </header>
</template>
