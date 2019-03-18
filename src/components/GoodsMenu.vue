<template>
  <div class="goods-menu">
      <ul class="list-group">
        <li class="list-group-item active">Кирпич</li>
        <li class="list-group-item">Сайдинг</li>
        <li class="list-group-item">Смеси строительные</li>
        <li class="list-group-item">Кровельные материалы</li>
        <li class="list-group-item">Пеноблоки</li>
      </ul>
  </div>
</template>

<script>

export default {
  name: "GoodsMenu",
  components: {
      
  },
  data() {
    return {};
  }
};
</script>
    
<style>

    .goods-menu{
        display: inline-block;
        border-radius: 5px;
        background: rgb(129, 137, 184);
        width: 200px;
    }
    .list-group-item{

         background: rgb(129, 137, 184);
    }

</style>
