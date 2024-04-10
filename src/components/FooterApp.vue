<script>
export default {
    name: 'FooterApp'
}
</script>

<template>
    <!--footer-section-->
    <section class="bg_dark" style="height: 225px;">
        <div class="me_container">
            <div class="row me_row">
                <div class="col-4 ">
                    <!--logo-->
                    <img src="/public/images/mt-2236-home-logo.png" alt="academic logo" style="width: 130px;">
                </div>
                <div class="col-3 px-2">
                    <!--social-->
                    <div class="text-capitalize text-light fw-light p-1" style="font-size: 14px;">
                        follow us
                    </div>
                    <div class="d-flex">
                        <!--social-icon-facebook-->
                        <div class="py-1 m-1">
                            <i class="fa-brands fa-facebook-f icon text-light" style="padding: 8px 10px;"></i>
                        </div>
                        <!--social-icon-mail-->
                        <div class="py-1 my-1">
                            <i class="fa-solid fa-paper-plane icon text-light" style="padding: 8px;"></i>
                        </div>
                        <!--social-icon-istagram-->
                        <div class="py-1 m-1">
                            <i class="fa-brands fa-instagram icon text-light" style="padding: 8px;"></i>
                        </div>
                    </div>
                </div>
                <!--subscribe-->
                <div class="col-5">
                    <div class="text-light fw-light" style="font-size: 10px;">
                        Subscribe to get the latest news, course updates, discounts, events
                    </div>
                    <!--input-text-->
                    <div class="py-2">
                        <input type="text" style="width: 100%; height: 35px; font-size: 9px;"class="fw-light text_grey p-3" value="Enter your e-mail here*">
                    </div>
                    <!--btn-->
                    <button type="button" class="btn px-4 py-2 fw-semibold bg_accent"
                        style="--bs-btn-padding-y: .25rem; --bs-btn-padding-x: .5rem; --bs-btn-font-size: .75rem;">
                        Subscribe
                    </button>
                </div>
            </div>
            <!--copyright-->
            <div class="text-light fw-light" style="font-size: 9px;">
                Copyright © 2021. All Rights Reserved.
            </div>
        </div>
    </section>

</template>

<style scoped>
.me_row {
    padding-top: 50px;
    padding-bottom: 20px;
}

.icon {
    font-size: 8px;
    border: 1px white solid;
    border-radius: 2px;
}
</style>