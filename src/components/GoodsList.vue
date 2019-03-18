<template>
  <div class="goods-list">
    <div class="container">
        <div class="row">
            <div class="col-3">
                <div class="card">
                    <img src="src\assets\block.jpg" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Название карточки</h5>
                        <p
                        class="card-text"
                        >Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                    </div>
                </div>
            </div>
            <div class="col-3">
                <div class="card">
                    <img src="src\assets\block.jpg" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Название карточки</h5>
                        <p
                        class="card-text"
                        >Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                    </div>
                </div>
            </div>
            <div class="col-3">
                <div class="card">
                    <img src="src\assets\block.jpg" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Название карточки</h5>
                        <p
                        class="card-text"
                        >Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                    </div>
                </div>
            </div>
            <div class="col-3">
                <div class="card">
                    <img src="src\assets\block.jpg" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Название карточки</h5>
                        <p
                        class="card-text"
                        >Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                    </div>
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col-3">
                <div class="card">
                    <img src="src\assets\block.jpg" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Название карточки</h5>
                        <p
                        class="card-text"
                        >Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                    </div>
                </div>
            </div>
            <div class="col-3">
                <div class="card">
                    <img src="src\assets\block.jpg" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Название карточки</h5>
                        <p
                        class="card-text"
                        >Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                    </div>
                </div>
            </div>
            <div class="col-3">
                <div class="card">
                    <img src="src\assets\block.jpg" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Название карточки</h5>
                        <p
                        class="card-text"
                        >Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                    </div>
                </div>
            </div>
            <div class="col-3">
                <div class="card">
                    <img src="src\assets\block.jpg" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Название карточки</h5>
                        <p
                        class="card-text"
                        >Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
  </div>
</template>

<script>

export default {
  name: "GoodsList",
  components: {
  },
  data() {
    return {};
  }
};
</script>
    
<style>
    .goods-list{
        position: absolute;
        margin-right: 10px;
        border-radius: 5px;
        display: inline-block;
        width: calc(100% - 260px);
        height: calc(100% - 90px);
        background:  rgb(129, 137, 184);
        right: 0;
    }
    .card{
        width: 90%;
        margin: 10px 10px 10px 0;
    }
    .card-img-top{
        width: 200px;

    }
</style>
