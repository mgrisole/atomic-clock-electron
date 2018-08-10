<template lang="pug">
  v-container#modulesContainer
    ModuleInterface
    ModuleInterface
</template>

<script>
  import ModuleInterface from './ModulesViews/ModuleInterface'

  export default {
    name: 'ModulesView',
    components: {
      ModuleInterface
    },
    methods: {
    }
  }
</script>

<style scoped lang="stylus">
#modulesContainer
  display flex
  flex-direction column
  height 100vh
</style>
