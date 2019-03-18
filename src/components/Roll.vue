<template>
  <div>
    <div id="carouselExampleControls" class="carousel slide" :class="{slideRight: isActive}" data-ride="carousel">
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img :src="roll[i].image" class="d-block w-100" alt="...">
          <div class="carousel-caption d-none d-md-block">
            <h4>{{roll[i].headText}}</h4>
            <p>{{roll[i].bottomText}}</p>
          </div>
        </div>
      </div>
      <a
        class="carousel-control-prev"
        href="#carouselExampleControls"
        role="button"
        data-slide="prev"
        @click="changeRollPrev()"
      >
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
      </a>
      <a
        class="carousel-control-next"
        href="#carouselExampleControls"
        role="button"
        data-slide="next"
        @click="changeRollNext()"
      >
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
      </a>
    </div>
    {{isActive}} 
  </div>
</template>

<script>
export default {
  name: "Roll",
  data() {
    return {
      isActive: false,
      i: 0,
      roll: [
        {
          headText: "Спецпредложение1",
          bottomText: "Кирпич по цене спичечного коробка",
          image:"src/assets/11.jpg"
        },
        {
          headText: "Спецпредложение2",
          bottomText: "Сайдинг за 10 руб",
          image: "src/assets/2.jpg"

        }
      ]
    };
  },
  methods:{
    changeRollNext(){
      this.isActive = !this.isActive;
      this.i = this.i + 1
      if (this.i === this.roll.length){
        this.i = 0
      }
      
      setTimeout(function() { this.isActive = !this.isActive;
      return this.isActive }, 2001);
      this.isActive = !this.isActive;
    },
    changeRollPrev(){
      this.i = this.i - 1
      if (this.i === -1){
        this.i = this.roll.length-1
      }
    }
  }
};
</script>

<style>
.carousel {
  margin: 20px auto 0 auto;
}
.carousel-item{
  height: 300px;
}

.slideRight{
    animation-name: slideRight;
    -webkit-animation-name: slideRight; 
 
    animation-duration: 2s; 
    -webkit-animation-duration: 2s;
 
    animation-timing-function: ease-in-out; 
    -webkit-animation-timing-function: ease-in-out;     
 
    visibility: visible !important; 
}
 
@keyframes slideRight {
    0% {
        transform: translateX(-150%);
    }
    
    100% {
        transform: translateX(0%);
    }   
}
 
@-webkit-keyframes slideRight {
    0% {
        -webkit-transform: translateX(-150%);
    }
    
    100% {
        -webkit-transform: translateX(0%);
    }
}
</style>