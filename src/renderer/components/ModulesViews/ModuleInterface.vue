<template lang="pug">
  v-layout.moduleInterface(column align-center)
    div
    | test
</template>

<script>
export default {
  name: 'ModuleInterface',
  props: {
    name: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="stylus">

  .moduleInterface
    justify-content center

</style>
