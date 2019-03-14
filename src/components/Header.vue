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
    width: 1000px;
    border-bottom: 1px solid rgb(175, 173, 173);
    border-top: 1px solid rgb(175, 173, 173);;
    box-shadow: 0 -3px 3px -3px rgba(0,0,0,0.5), 0 3px 3px -3px rgba(0,0,0,0.5);
    margin-left:auto;
    margin-right:auto;
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
    font-weight: bold;
  }

</style>
