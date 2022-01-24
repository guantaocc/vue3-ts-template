<template>
  <div id="app-root">
    App root
    <demo msg="hello-world" />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import demo from './components/demo'
export default defineComponent({
  name: 'App',
  components: {
    demo
  }
})
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
