<script>
import WelcomeApp from './WelcomeApp.vue'
import ServiceApp from './ServiceApp.vue'
import ImageGalleryApp from './ImageGalleryApp.vue'
export default {
    name: 'MainApp',
    components: {
        WelcomeApp,
        ServiceApp,
        ImageGalleryApp
    }
}
</script>

<template>
    <!--welcome-section-->
    <WelcomeApp />
    <!--service-section-->
    <ServiceApp />
    <!--grid-image-section-->
    <ImageGalleryApp />




</template>

<style></style>