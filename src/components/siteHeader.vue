<template>
    <header>
        <h1>{{storyTitle}}</h1>
        <!-- <siteNav></siteNav> -->
    </header>    
</template>

<script>
import siteNav from '@/components/siteNav'

export default {
  name: 'siteHeader',
  components: {
    siteNav
  },
  data () {
    return {
      storyTitle: 'Story Title'
    }
  }
}
</script>

<style scoped lang="scss">

    header {
        text-align: center;
    }

</style>
