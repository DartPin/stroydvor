<template>
  <div id="app">
    <Header @newName="componentName = $event"></Header>
    <component :is="componentName"></component>
    <Footer></Footer>
    
    
  </div>
</template>

<script>
import Header from "./components/Header.vue"
import Main from "./components/Main.vue"
import Footer from "./components/Footer.vue"
import Goods from "./components/Goods.vue"
import Contacts from "./components/Contacts.vue"

export default {
  name: 'app',
  components: {
    Header,
    Main,
    Goods,
    Footer,
    Contacts
  },
  data () {
    return {
      componentName: "Main",
    }
  }
}
</script>

<style>
html {
  position: relative;
  min-height: 100%;
}
body{
  background: rgb(221, 217, 210)
}
</style>
