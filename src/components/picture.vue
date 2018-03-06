<template>
    <figure>
        <img :src="imgSrc" :alt="imgCaption">
        <caption>{{imgCaption}}</caption>
    </figure>  
</template>

<script>
export default {
  name: 'illustration',
  data () {
    return {
      imgSrc: '../static/logo.png',
      imgCaption: 'image logo'
    }
  }
}
</script>

<style scoped lang="scss">

  figure {
    text-align: center;

    img {

    }

    caption {
      display: block;
    }
  }

</style>
