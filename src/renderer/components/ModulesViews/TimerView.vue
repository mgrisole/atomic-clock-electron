<template lang="pug">
  v-container.moduleTimer
    v-layout(column align-center)
      | {{timer}}
</template>

<script>
import moment from 'moment'
import ModuleInterface from './ModuleInterface'

export default {
  name: 'TimerView',
  components: {
    ModuleInterface
  },
  data () {
    return {
      timer: ''
    }
  },
  methods: {
    update () {
      setInterval(() => {
        this.timer = moment().format('LTS')
      }, 1000)
    }
  },
  created () {
    moment.locale('fr')
    this.timer = moment().format('LTS')
  },
  mounted () {
    this.update()
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="stylus">
</style>
