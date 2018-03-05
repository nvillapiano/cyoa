<template>
    <header>
        <h1>{{header_text}}</h1>
        <h2>foo</h2>
    </header>
</template>

<script>
export default {
  name: 'header',
  data () {
    return {
      header_text: 'This is a header'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    header {
        background: red;
    }
</style>
