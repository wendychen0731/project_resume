

<template>
  <MainHeader />
  <RouterView />
</template>

<script>
import { RouterLink, RouterView } from 'vue-router'
import MainHeader from './components/mainHeader.vue'

export default {
  components: {
    RouterView,
    MainHeader,
  },
  data() {
    return {

    }
  },
  created() {

  },
  methods: {

  },

}
</script>

<style scoped>

</style>
