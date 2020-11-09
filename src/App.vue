<template lang="pug">
  #App
    Top
    Left
    Right
    Footer
</template>

<script>
import Top from './components/Top.vue'
import Left from './components/Left.vue'
import Right from './components/Right.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Top,
    Left,
    Right,
    Footer
  }
}
</script>
