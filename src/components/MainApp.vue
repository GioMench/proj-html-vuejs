<script>
import WelcomeApp from './WelcomeApp.vue'
import ServiceApp from './ServiceApp.vue'
import ImageGalleryApp from './ImageGalleryApp.vue'
import PlayBannerApp from './PlayBannerApp.vue'
import CoursesApp from './CoursesApp.vue'
import StepBannerApp from './StepBannerApp.vue'
import EventsApp from './EventsApp.vue'
export default {
    name: 'MainApp',
    components: {
        WelcomeApp,
        ServiceApp,
        ImageGalleryApp,
        PlayBannerApp,
        CoursesApp,
        StepBannerApp,
        EventsApp
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
    <PlayBannerApp />
    <!--courses-section-->
    <CoursesApp />
    <!--step-banner-section-->
    <StepBannerApp />
    <!--events-section-->
    <EventsApp />




</template>

<style></style>