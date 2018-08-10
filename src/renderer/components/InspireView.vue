<template lang="pug">
  v-layout(column justify-center)
    v-flex
      img(src="/static/v.png" alt="Vuetify.js" class="mb-5")
      blockquote(class="text-xs-center")
        | &#8221;First, solve the problem. Then, write the code.&#8221;
        footer
          small
            em
              | &mdash; John Johnson
</template>

<style scoped lang="stylus">
  img
    margin-left: auto
    margin-right: auto
    display: block
</style>