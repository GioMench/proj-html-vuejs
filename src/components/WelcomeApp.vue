<script>
export default{
    name: 'WelcomeApp'
}
</script>
<template>

    <!--back-img-welcome-section-->
    <img class=" img_top" src="/public/images/mt-2236-home-bg1.jpg" alt="">
    <!--welcome-section-->
    <section class="container-fluid welcome_section">
        <!--phone-icon-left-->
        <div class="align-middle">
            <i class="fa-solid fa-phone text_accent"></i>
        </div>
        <!--welcome-info-->
        <div class="me_container" style="height: 100%;">
            <div class="me_container_xs" style="height: 100%">
                <!--welcome-fake-button-->
                <span class="text-dark fw-semibold text-uppercase bg_accent"
                    style="padding: 1px 6px; border-radius: 20px; font-size: 10px;">
                    Welcome
                </span>
                <!--title-->
                <h1 class="text-uppercase text-light fw-medium">
                    academic chess for <span class="fst-italic text_accent" >everyone</span>
                </h1>
                <!--explain-academy-->
                <p class="text-light fw-light" style="font-size: 12px;">
                    We are dedicated to broadening and developing chess as art, 
                    recreation, and as a significant element of culture in Northern
                    California
                </p>
                <!--button-for-more-->
                <button type="button" class="btn px-4 py-2 fw-semibold bg_accent" style="--bs-btn-padding-y: .25rem; --bs-btn-padding-x: .5rem; --bs-btn-font-size: .75rem;">Enroll Now</button>
                <button type="button" class="btn btn-outline-light mx-2 px-4 py-2 fw-semibold" style="--bs-btn-padding-y: .25rem; --bs-btn-padding-x: .5rem; --bs-btn-font-size: .75rem;border-width: 1.5px;">Learn More</button>

            </div>
        </div>
    </section>
</template>

<style scoped>
.img_top {
    max-width: 100%;
    height: 100%;
    position: absolute;
    top: 0;
    z-index: -1;
}

.welcome_section {
    z-index: 3;
    height: 460px;
    position: relative;
}

.fa-phone {
    font-size: 25px;
    background-color: #FFFFFF;
    padding: 10px;
    border-radius: 50%;
    margin-left: 0;
    position: absolute;
    top: 45%;
}

</style>