<template>
  <div id="app">
    <Header></Header>
    <Roll></Roll>
    <mat-menu></mat-menu>
    <about></about>
  </div>
</template>

<script>
import Header from "./components/Header.vue"
import Roll from "./components/Roll.vue"
import MatMenu from "./components/Mat-menu.vue"
import About from "./components/About.vue"

export default {
  name: 'app',
  components: {
    Header,
    Roll,
    MatMenu,
    About
  },
  data () {
    return {
     
    }
  }
}
</script>

<style>

</style>
