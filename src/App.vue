<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Hello Vue 3.0 + Vite" />
</template>

<script lang="ts">
import HelloWorld from './components/HelloWorld.vue'
import "./assets/app.css"
import info from "./assets/info.json"

const tsTest: string = "Vite for Vue 3.0"

export default {
  name: 'App',
  components: {
    HelloWorld
  },
  mounted() {
    console.log(tsTest)
    console.log(info.name + " | " + info.website)
  }
}
</script>
