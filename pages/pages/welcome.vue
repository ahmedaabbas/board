<template lang="pug">
div
  FullPage
    .u-text-center
      img(src='~assets/img/welcome.png', srcset='~assets/img/welcome.png 1x, ~assets/img/welcome@2x.png 2x')

      h1 Welcome to Board!
      p Lets go to your profile& team set up, it’s two steps and will take arround a minute
      button.button.is-primary Get started


</template>



<script>
import FullPage from '~/components/FullPage'
export default {
  layout: 'minimal',
  components: {
    FullPage
  }
}
</script>
