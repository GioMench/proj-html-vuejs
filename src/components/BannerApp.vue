<script>

export default {
    name: 'BannerApp',

}
</script>

<template>
    <!--play-banner-section-->
    <section class="banner bg_accent">
        <div class="me_container d-flex justify-content-between align-items-center p-4" style="height: 100%;">
            <img src="/public/images/mt-2236-home-icon5.png" alt="chess horse" style="width: 65px;">
            <div>
                <h3 class="text-uppercase fw-semibold">
                    play & learn
                </h3>
                <div class="fw-light" style="font-size: 14px;">
                    Take a look into our day to day life here at Chess School
                </div>

            </div>
            <button type="button" class="btn btn-outline-dark px-5 py-2 fw-semibold"
                style="--bs-btn-padding-y: .25rem; --bs-btn-padding-x: .5rem; --bs-btn-font-size: .75rem;">
                Learn More
            </button>
        </div>
    </section>





</template>

<style scoped>
.banner {
    height: 135px;
}
</style>