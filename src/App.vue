<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Hello Vue 3.0 + Vite" />
</template>

<script lang="ts">
import HelloWorld from './components/HelloWorld.vue'
const tsTest: string = "Vite for Vue 3.0"

export default {
  name: 'App',
  components: {
    HelloWorld
  },
  mounted() {
    console.log(tsTest)
  }
}
</script>
