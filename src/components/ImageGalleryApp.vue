<script>
export default {
    name: 'ImageGalleryApp'

}
</script>
<template>

    <!--gallery-image-section-->
    <div class="d-flex">
        <img src="/public/images/mt-2236-home-gallery1.jpg" class="img-fluid" alt="...">
        <img src="/public/images/mt-2236-home-gallery2.jpg" class="img-fluid" alt="...">
        <img src="/public/images/mt-2236-home-gallery3.jpg" class="img-fluid" alt="...">
        <img src="/public/images/mt-2236-home-gallery4.jpg" class="img-fluid" alt="...">
    </div>
</template>

<style scoped>
img{
    width: calc(100% / 4);
}
</style>