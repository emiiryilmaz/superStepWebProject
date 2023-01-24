<template>
    <div>
      <VueSlickCarousel :arrows="true" :dots="true">
        <div> <img src="https://cdn-ss.akinon.net/cms/2022/11/16/c7be747c-731f-49c0-b78f-325914edcbab.jpg" /></div>
        <div> <img src="https://cdn-ss.akinon.net/cms/2022/11/16/3ed1d39f-1ce5-4d2b-a23f-e73b9ca383ce.jpg" /></div>
        <div><img src="https://cdn-ss.akinon.net/cms/2022/11/16/e0eecf82-44e2-4e4c-a1cd-21ce03c929a3.jpg" /></div>
        <div><img src="https://cdn-ss.akinon.net/cms/2022/11/16/274e7f76-02a8-449b-8662-cf7c6ac40860.jpg" /></div>
      </VueSlickCarousel>
    </div>
  </template>
  
  <script>
  import VueSlickCarousel from 'vue-slick-carousel'
  import 'vue-slick-carousel/dist/vue-slick-carousel.css'
  // optional style for arrows & dots
  import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'
  export default {
    data() {
      return {
        slickOptions: {
          autoplay: true,
        }
      }
    },
    name: 'MyComponent',
    components: { VueSlickCarousel },
  }
  </script> 
  <style scoped>
  img {
    margin-left: auto;
    margin-right: auto;
  }
  </style>