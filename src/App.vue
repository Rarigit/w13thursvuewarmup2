<template>
  <div id="app">
    <ProductHero/>
    <ProductInfo/>
    <ProductGallery/>
    <PageFooter/>
  </div>
</template>

<script>
import ProductHero from "@/components/ProductHero.vue";
import ProductInfo from "@/components/ProductInfo.vue";
import ProductGallery from "@/components/ProductGallery.vue";
import PageFooter from "@/components/PageFooter.vue";

export default {
  name: 'App',
  components: {
    ProductHero,
    ProductInfo,
    ProductGallery,
    PageFooter
  }
}
</script>

<style>
html{
  background-color: bisque;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
