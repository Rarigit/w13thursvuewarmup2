<template>
    <div>
        <p>
            Funko's line of Pop! figures are based on the Japanese style known as Chibi, which means short and cute. 
            The heads of the Pop! Vinyl figures are the most recognizable part as they are substantially larger than the bodies in which they sit. 
            They also feature large solid black eyes widely spaced on the face. Typically the mouth and eyebrows are notably missing from a standard Pop! 
        </p>
        <ProductGallery/>
    </div>
</template>

<script>
import ProductGallery from "./ProductGallery.vue";
    export default {
        name : "ProductInfo",
        components: {
            ProductGallery
        },
    }
</script>

<style scoped>
    p{
        width: 75vw;
        position: relative;
        left: 50%;
        transform: translateX(-50%);
    }
</style>