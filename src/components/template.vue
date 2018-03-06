<template>
    <div>
        <h1>{{value}}</h1>
        <subComponent></subComponent>
    </div>    
</template>

<script>
import component from '@/components/component'

export default {
  name: 'component',
  components: {
    subComponent
  },
  data () {
    return {
      key: 'value'
    }
  }
}
</script>

<style scoped lang="scss">

</style>
