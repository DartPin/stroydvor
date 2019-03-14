<template>
  <div>
    <div id="carouselExampleControls" class="carousel slide" data-ride="carousel">
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img src="src\assets\1.jpg" class="d-block w-100" alt="...">
          <div class="carousel-caption d-none d-md-block">
            <h5>спецпредложение</h5>
            <p>кирпич по цене спичечного коробка</p>
          </div>
        </div>
        <div class="carousel-item">
          <img src="src\assets\2.jpg" class="d-block w-100" alt="...">
          <div class="carousel-caption d-none d-md-block">
            <h5>...</h5>
            <p>...</p>
          </div>
        </div>
        <div class="carousel-item">
          <img src="src\assets\3.jpg" class="d-block w-100" alt="...">
          <div class="carousel-caption d-none d-md-block">
            <h5>...</h5>
            <p>...</p>
          </div>
        </div>
      </div>
      <a
        class="carousel-control-prev"
        href="#carouselExampleControls"
        role="button"
        data-slide="prev"
      >
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
      </a>
      <a
        class="carousel-control-next"
        href="#carouselExampleControls"
        role="button"
        data-slide="next"
      >
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
      </a>
    </div>
  </div>
</template>

<script>
export default {
  name: "Roll",
  data() {
    return {};
  }
};
</script>

<style>
.carousel {
  margin: 20px auto 0 auto;
  width: 1000px;
}
</style>