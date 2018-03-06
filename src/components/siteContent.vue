<template>
    <div class="site-content">
        <h2>
            {{chapterTitle}}
        </h2>
        <illustration></illustration>
        <pageCopy></pageCopy>
        <inPageNav></inPageNav>
    </div>
</template>

<script>
import illustration from '@/components/picture'
import pageCopy from '@/components/pageCopy'
import inPageNav from '@/components/inPageNav'

export default {
  name: 'siteContent',
  components: {
    illustration,
    pageCopy,
    inPageNav
  },
  data () {
    return {
      chapterTitle: 'Chapter 1: The Beginning'
    }
  }
}
</script>

<style scoped lang="scss">

    .site-content {

        h1, h2 {
            text-align: center;
        }
    }

</style>
