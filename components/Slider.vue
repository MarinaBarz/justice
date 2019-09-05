<template>
  <div class="carousel">
    <div class="carousel-body" :style="{transform: 'translateX(-' + indexCarousel*100 + '%)' }">
      <div class="carousel-item">
        <img src="/public/img/carousel/l1.png" alt srcset>
      </div>
      <div class="carousel-item">
        <img src="/public/img/carousel/l2.png" alt srcset>
      </div>
      <div class="carousel-item">
        <img src="/public/img/carousel/l3.png" alt srcset>
      </div>
      <div class="carousel-item">
        <img src="/public/img/carousel/l4.png" alt srcset>
      </div>
      <div class="carousel-item">
        <img src="/public/img/carousel/l5.png" alt srcset>
      </div>
      <div class="carousel-item">
        <img src="/public/img/carousel/l6.png" alt srcset>
      </div>
      <div class="carousel-item">
        <img src="/public/img/carousel/l7.png" alt srcset>
      </div>
      <div class="carousel-item">
        <img src="/public/img/carousel/l8.png" alt srcset>
      </div>
    </div>
    <ul class="carousel-indicators">
      <li
        v-for="(item, index) in indicators"
        :key="index"
        :class="{active: index == indexCarousel}"
      ></li>
    </ul>
  </div>
</template>
<script>
export default {
  data() {
    return {
      indexCarousel: 0,
      indicators: [0, 1]
    };
  },
  methods: {
    slider() {
      this.indexCarousel++;

      if (this.indexCarousel === 2) {
        this.indexCarousel = 0;
      }
    }
  },
  mounted() {
    window.onload = () => setInterval(this.slider, 4000);
  }
};
</script>

