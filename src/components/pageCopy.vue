<template>
    <div class="page-copy" v-html="pageCopy">        
    </div>
</template>

<script>
export default {
  name: 'pageCopy',
  data () {
    return {
      pageCopy: "<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>"
    }
  }
}
</script>

<style scoped lang="scss">

    .page-copy {
        font-size: 2rem;
        line-height: 1.5;
    }

</style>
