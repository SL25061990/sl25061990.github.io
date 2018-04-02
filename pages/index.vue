<template lang="pug">
.page
  app-logo
</template>

<script>
import AppLogo from '~/components/AppLogo.vue'

export default {
  head () {
    return {
      title: 'Главная',
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: 'Главная страница'
        }
      ]
    }
  },
  data () {
    return {

    }
  },
  components: {
    AppLogo
  }
}
</script>

<style lang="stylus" scoped>

</style>
