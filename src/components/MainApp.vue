<script>
import WelcomeApp from './WelcomeApp.vue'
import ServiceApp from './ServiceApp.vue'
import ImageGalleryApp from './ImageGalleryApp.vue'
import BannerApp from './BannerApp.vue'
import CoursesApp from './CoursesApp.vue'
export default {
    name: 'MainApp',
    components: {
        WelcomeApp,
        ServiceApp,
        ImageGalleryApp,
        BannerApp,
        CoursesApp
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
    <!--play-banner-section-->
    <BannerApp />
    <!--courses-section-->
    <CoursesApp />




</template>

<style></style>