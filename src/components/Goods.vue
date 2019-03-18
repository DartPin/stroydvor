<template>
  <div class="goods">
    <GoodsMenu></GoodsMenu>
    <GoodsList></GoodsList>
  </div>
</template>

<script>
import GoodsMenu from "./GoodsMenu.vue"
import GoodsList from "./GoodsList.vue"

export default {
  name: "Goods",
  components: {
      GoodsMenu,
      GoodsList
  },
  data() {
    return {};
  }
};
</script>
    
<style>
    .goods{
        margin: 20px 0 0 0;    
    }
    .goods-menu{
        border-radius: 5px;
        background: rgb(129, 137, 184);
        width: 200px;
    }
    .list-group-item{

         background: rgb(129, 137, 184);
    }

</style>
