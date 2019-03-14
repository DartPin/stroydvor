<template>
  <div class="container">
    <div class="row">
      <div class="col-4">
        <div class="card" style="width: 18rem;">
          <img src="src\assets\logo.gif" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Название карточки</h5>
            <p
              class="card-text"
            >Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <a href="#" class="btn btn-primary">Переход куда-нибудь</a>
          </div>
        </div>
      </div>
      <div class="col-4">
          <div class="card" style="width: 18rem;">
          <img src="src\assets\logo.gif" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Название карточки</h5>
            <p
              class="card-text"
            >Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <a href="#" class="btn btn-primary">Переход куда-нибудь</a>
          </div>
        </div>
      </div>
      <div class="col-4">
          <div class="card" style="width: 18rem;">
          <img src="src\assets\logo.gif" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Название карточки</h5>
            <p
              class="card-text"
            >Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <a href="#" class="btn btn-primary">Переход куда-нибудь</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "app",
  data() {
    return {};
  }
};
</script>

<style>
.container {
  margin-top: 20px;
  width: 1000px;
}
.card{
    box-shadow: 0 0 3px  rgba(0,0,0,0.5)
}
</style>