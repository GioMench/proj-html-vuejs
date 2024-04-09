<script>
export default {
    name: 'EventsApp',
}
</script>



<template>
    <!--service-section-->
    <section class="me_container container py-5">
        <!--title-->
        <h3 class="text-center text-capitalize fw-semibold">
            our events
        </h3>
        <div class="text-center fw-light text_grey" style=" font-size: 15px;">
            Chess is fun and we are happy to prove it at our events!
        </div>

        <div class="row py-3">
            <div class="col d-flex my-3">
                <img src="/public/images/mt-2236-home-img4.jpg" alt="child">
                <div class="d-flex flex-column justify-content-center p-3">
                    <h6>
                        Grand Summer Tournament of 2021
                    </h6>
                    <p class="text_grey fw-light" style="font-size: 11px;">
                        Join us for the Grand Summer Tournament 2021. Held every year on the first Sunday of summer, our
                        Grand Summer Tournament chess masters and beginners from North California.
                        We have competitions for different levels of chess mastery with amazing prizes
                        awarded at each level.
                    </p>
                </div>
                <div class="d-flex flex-column justify-content-center col-2 ">
                    <button type="button" class="btn px-4 py-2 fw-semibold bg_accent mx-1"
                        style="--bs-btn-padding-y: .25rem; --bs-btn-padding-x: .5rem; --bs-btn-font-size: .75rem;">Register</button>
                </div>


            </div>

            <div class="col d-flex my-3">
                <img src="/public/images/mt-2236-home-img5.jpg" alt="child">
                <div class="d-flex flex-column justify-content-center p-3">
                    <h6>
                        World Chess Day
                    </h6>
                    <p class="text_grey fw-light" style="font-size: 11px;">
                        Celebrated on July 20 every year, World Chess Day is one of the biggest events at our school. Be ready for fun tournaments and big prizes. Registration is obligatory!
                    </p>
                </div>
                <div class="d-flex flex-column justify-content-center col-2 ">
                    <button type="button" class="btn px-4 py-2 fw-semibold bg_accent mx-1"
                        style="--bs-btn-padding-y: .25rem; --bs-btn-padding-x: .5rem; --bs-btn-font-size: .75rem;">Register</button>
                </div>


            </div>



        </div>
    </section>
</template>

<style scoped>
img {
    width: 250px;
}
</style>