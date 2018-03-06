<template>
    <footer v-html="footerCopy">
    </footer>
</template>

<script>
export default {
  name: 'siteFooter',
  data () {
    return {
      footerCopy: 'CYOA Framework &copy; 2018'
    }
  }
}
</script>

<style scoped lang="scss">

  footer {
    text-align: center;
    margin: 2rem 0 0;
    font-size: 1.4rem;
  }

</style>
