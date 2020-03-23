<template>
    <navbar />
     
</template>

<style>
    .fade-enter-active, .fade-leave-active {
      transition: opacity .5s
    }
    .fade-enter, .fade-leave-active {
      opacity: 0
    }
</style>

<script>
import navbar from '@/components/NavBar.vue'
export default {
  name: 'app',
  components: {
    navbar
  }
}
</script>