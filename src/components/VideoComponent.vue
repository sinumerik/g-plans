<template>
  <div class="results">
    <div class="container">
      <div class="results-wrap">
        <span class="results-title">
          Say <span class="results-title_italic">“hello”</span> to the <br />
          realest results
        </span>
        <p class="results-text">
          The top G-Plans success stories are almost always from clients in our
          commitment program.
        </p>
      </div>
    </div>
    <div class="results-container">
      <swiper
        :modules="modules"
        :slidesPerView="1.5"
        :centeredSlides="true"
        :pagination="{ clickable: true }"
        @slideChange="showBg()"
      >
        <swiper-slide v-for="slide in results" :key="slide.id">
          <div class="results-slide">
            <video controls preload :poster="slide.poster">
              <source :src="slide.url" type="video/mp4" />
            </video>
            <div
              v-if="slide.showPlay"
              class="results-slide__info"
              @click="hideBg(slide)"
            >
              <span class="results-slide__name">{{ slide.name }}</span>
              <span class="results-slide__text">{{ slide.text }}</span>
            </div>
          </div>
        </swiper-slide>
      </swiper>
    </div>
  </div>
</template>
<script>
// import Swiper core and required modules
import { Pagination } from "swiper/modules";

// Import Swiper Vue.js components
import { Swiper, SwiperSlide } from "swiper/vue";

// Import Swiper styles
import "swiper/css";
import "swiper/css/pagination";

// Import Swiper styles
export default {
  components: {
    Swiper,
    SwiperSlide,
  },
  data() {
    return {
      results: [
        {
          id: 0,
          name: "Rebecca",
          text: "Lost 67 lbs and 13 inches!",
          url: "/g-plans/src/assets/images/results/ShiftReb.mp4",
          poster: "/g-plans/src/assets/images/results/ShiftReb.png",
          showPlay: true,
        },
        {
          id: 1,
          name: "Amber",
          text: "Lost 52 lbs and 9% body fat!",
          url: "/g-plans/src/assets/images/results/ShiftAmb.mp4",
          poster: "/g-plans/src/assets/images/results/ShiftAmb.png",
          showPlay: true,
        },
        {
          id: 2,
          name: "Alyssa",
          text: "Lost 37 lbs so far!",
          url: "/g-plans/src/assets/images/results/ShiftAly.mp4",
          poster: "/g-plans/src/assets/images/results/ShiftAly.png",
          showPlay: true,
        },
      ],
    };
  },
  setup() {
    return {
      modules: [Pagination],
    };
  },
  methods: {
    showBg() {
      this.results.forEach((item) => {
        item.showPlay = true;
      });

      const video = document.querySelectorAll("video");

      video.forEach((v) => {
        v.pause();
      });
    },
    hideBg(slide) {
      this.results.forEach((item, i) => {
        if (item === slide) {
          item.showPlay = false;

          const video = document.querySelectorAll("video");

          video.forEach((v, idx) => {
            if (i === idx) {
              v.play();
            }
          });
        }
      });
    },
  },
};
</script>
