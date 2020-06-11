<template>
  <div class="container">
    <section class="my-4 ml-10">
      <div class="flex flex-wrap justify-center mx-auto">
        <div class="w-1/3">
          <img src="~/assets/avataaars.svg" alt="Avatar" />
        </div>
        <div class="w-2/5">
          <h1 class="py-2 text-2xl font-bold text-center">
            Hey, I'm Ed, a web developer from Planet Earth.
          </h1>
          <p>
            Thanks for checking out my web page. Here, you can check out my work
            and get a feel for where I'm planning to take this wonderful ride of
            technology and design.
          </p>
          <p>
            If you are looking to hire me for a project, I am ready for you!
            Please click the 'Hire Me' button and we can get this started. You
            will feel much better working with a real developer whom is
            dedicated to making sure you are happy with your website at the end
            of the day. Always cool to have something special that looks nice
            that you want to show off.
          </p>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'
import HeaderTop from '~/components/HeaderTop.vue'

export default {
  components: {
    Logo,
    HeaderTop
  }
}
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
  @apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
</style>
