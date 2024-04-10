<script>
export default {
    name: 'StepBannerApp'
}
</script>

<template>


    <!--background-img-->
    <img class="img_blackwhite" src="/public/images/mt-2236-home-bg2.jpg" alt="chess black and white">
    <!--step-banner-section-->
    <section class="banner">

        <div class="me_container step_section d-flex justify-content-between align-items-center p-4" style="height: 100%;">
            <div>
                <div class="text-uppercase fw-semibold text-light" style="font-size: 30px;">
                    take the <span class="text_accent">first step</span>
                </div>
                <div class="fw-light text-light py-1" style="font-size: 11.5px;">
                    The fascinating world of chess has its doors open for anyone
                </div>

            </div>
            <button type="button" class="btn px-4 py-2 fw-semibold bg_accent" style="--bs-btn-padding-y: .25rem; --bs-btn-padding-x: .5rem; --bs-btn-font-size: .75rem;">View More</button>
        </div>
    </section>

</template>

<style scoped>
.banner {
    height: 210px;
}

.img_blackwhite {
    width: 100%;
    height: 210px;
    z-index: -1;
    position: absolute;

}

.step_section {
    z-index: 3;
}
</style>