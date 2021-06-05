<template>
  <div class="app">
    <Example name="Gabriel" lastName="Caiana" />
  </div>
</template>

<script>
import Example from './components/Example.vue'
export default {
  components: {
    Example
  },
  setup () {
    

    return {}
  }
}
</script>

<style lang="scss" scoped>
 .app {
   height: 100vh;
   display: flex;
   align-items: center;
   justify-content: center;
   font-family: -apple-system, 'Open Sans', 'Helvetica Neue', sans-serif;
 }
</style>
