<template>
    <div></div>
</template>

<script>
import siteHeader from '@/components/siteHeader'
import content from '@/components/content'
import siteFooter from '@/components/siteFooter'

export default {
  name: 'main',
  components: {
    siteHeader,
    content,
    siteFooter
  }
}
</script>

<style lang="scss">
// global styles
    // include normalize
    @import "../scss/normalize";

    body {
        font-family: 'Crimson Text', serif;
    }
</style>
