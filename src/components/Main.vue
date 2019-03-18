<template>
  <div>
    
    <Roll></Roll>
    <mat-menu></mat-menu>
    <about></about>
    
    
    
  </div>
</template>

<script>

import Roll from "./Roll.vue"
import MatMenu from "./Mat-menu.vue"
import About from "./About.vue"


export default {
  name: 'Main',
  components: {
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
