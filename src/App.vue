<template>
  <div id="app">
    <siteHeader></siteHeader>
    <siteContent></siteContent>
    <siteFooter></siteFooter>

    <router-view/>
  </div>
</template>

<script>
import siteHeader from '@/components/siteHeader'
import siteContent from '@/components/siteContent'
import siteFooter from '@/components/siteFooter'

export default {
  name: 'App',
  components: {
    siteHeader,
    siteContent,
    siteFooter
  }
}
</script>

<style lang="scss">
// global styles
    // include normalize
    @import "./scss/normalize";
    @import "./scss/colors";

    html, body {
        font-size: 62.5%;
        font-family: 'Crimson Text', serif;
    }

    #app {
      font-size: 1.6rem;
      width: 100%;
      max-width: 55rem;
      margin: 0 auto;
      padding: 2rem 0;

      h1 {
        font-size: 4rem;
      }
    }

</style>
