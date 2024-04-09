<script>
import WelcomeApp from './WelcomeApp.vue'
import ServiceApp from './ServiceApp.vue'
export default {
    name: 'MainApp',
    components: {
        WelcomeApp,
        ServiceApp,
    }
}
</script>

<template>
    <!--welcome-section-->
    <WelcomeApp />
    <!--service-section-->
    <ServiceApp />




</template>

<style></style>