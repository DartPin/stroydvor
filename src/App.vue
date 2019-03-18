<template>
  <div id="app">
    <Header></Header>
    <Contacts></Contacts>
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
