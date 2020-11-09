<template lang="pug">
  #left
    #menu
      p 社團介紹
      table
        tr(v-for="(club, index) in clubs" :key='club')
          td
            a(href="#", title="title") {{club}}
    #date 20202022
</template>

<script>
export default {
  name: 'Left',
  data () {
    return {
      clubs: ['吉他社', '熱舞社', '棒球社', '羽球社', '足球社', '童軍社']
    }
  }
}
</script>
