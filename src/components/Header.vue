<template>
    <header>
      <div class="logo"><img class="logo-img" src="src\assets\logo.gif" alt=""></div>
      <div class="nav-menu"> 
        <div class="nav-item-block">
          <div class="nav-item">о нас</div>
          <div class="nav-item">товар</div>
          <div class="nav-item">контакты</div>
        </div>        
      </div>
      <div class="phone">тел. +7 (912) 345 67 89</div>
    </header>
</template>

<script>
export default {
  name: 'Header',
  data () {
    return {
      
    }
  },
  methods: {
    newComponentName: function(value){
      this.$emit('newName', value)
    }
  }
}
</script>

<style>
  header{
    position: relative;
    margin: 10px 0 0 0; 
    border-bottom: 2px solid rgb(43, 18, 110);
    border-top: 1px solid rgb(43, 18, 110);;
    box-shadow: 0 -3px 6px -3px rgba(0,0,0,0.5), 0 3px 3px -3px rgba(0,0,0,0.5);
    margin-left:auto;
    margin-right:auto;
    background: rgb(129, 137, 184);
  }
  .logo{
    width: 40px;
    height: 40px;
    display: inline-block;
  }
  .logo-img{
    width: 70px;
    height: 70px;
    margin: -10px 0 0 20px;
  }
  .nav-menu{
    display: inline-block;
    width: 90%;
  }
  .nav-item-block{
    position: relative;
    margin-left:auto;
    margin-right:auto;
    width: 50%;
  }
  .nav-item{
    padding: 0 0 10px 0;
    width: 30%;
    display: inline-block;
    text-transform: uppercase;
    font-size: 25px;
    color: rgb(36, 37, 51)
  }
  .phone{
    margin: -45px 20px 0 0;
    position: absolute;
    font-size: 25px;
    color: rgb(36, 37, 51);
    right: 0;
    font-weight: bold;
  }

</style>
