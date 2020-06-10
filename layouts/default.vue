<template>
  <div class="Site">
    <HeaderTop />
    <main class="Site-content">
      <nuxt />
    </main>
    <FooterBottom />
  </div>
</template>

<style>
.Site {
  display: flex;
  min-height: 100vh;
  flex-direction: column;
}

.Site-content {
  flex: 1;
}
</style>
<script>
import Logo from '~/components/Logo.vue'
import HeaderTop from '~/components/HeaderTop.vue'
import FooterBottom from '~/components/FooterBottom.vue'

export default {
  components: {
    Logo,
    HeaderTop,
    FooterBottom
  }
}
</script>
