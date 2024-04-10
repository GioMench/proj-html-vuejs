<script>
export default {
    name: 'CoursesApp'
}
</script>

<template>
    <div class="me_container py-5">
        <!--title-->
        <h3 class="text-center  fw-semibold">
            Courses
        </h3>
        <div class="text-center fw-light text_grey" style=" font-size: 15px;">
            To keep up with the costantly rising standards of play
        </div>

        <div class="row py-4">
            <div class="col-4">
                <div class="card me_card">
                    <img src="/public/images/mt-2236-home-img1.jpg" alt="" style="width: 100%;">
                    <div class="card-body text-center">
                        <h5 class="card-title text-capitalize fw-semibold">
                            garry kasparov's masterclass
                        </h5>
                        <p class="card-text fw-light" style="font-size: 12px;">
                           Learn the tips, tricks, and stategies from one of the best masters
                        </p>
                            <h5 class="card-title fw-semibold">
                                $456
                            </h5>
                            <button type="button" class="btn px-4 py-2 fw-semibold bg_accent" style="--bs-btn-padding-y: .25rem; --bs-btn-padding-x: .5rem; --bs-btn-font-size: .75rem;">View More</button>
                    </div>
                </div>
            </div>
            <div class="col-4">
                <div class="card me_card">
                    <img src="/public/images/mt-2236-home-img1.jpg" alt="" style="width: 100%;">
                    <div class="card-body text-center">
                        <h5 class="card-title text-capitalize fw-semibold">
                            garry kasparov's masterclass
                        </h5>
                        <p class="card-text fw-light" style="font-size: 12px;">
                           Learn the tips, tricks, and stategies from one of the best masters
                        </p>
                            <h5 class="card-title fw-semibold">
                                $456
                            </h5>
                            <button type="button" class="btn px-4 py-2 fw-semibold bg_accent" style="--bs-btn-padding-y: .25rem; --bs-btn-padding-x: .5rem; --bs-btn-font-size: .75rem;">View More</button>
                    </div>
                </div>
            </div>

        </div>

        <div class="text-center py-1">
            <button type="button" class="btn btn-outline-dark px-4 py-2 fw-semibold"
                style="--bs-btn-padding-y: .25rem; --bs-btn-padding-x: .5rem; --bs-btn-font-size: .75rem;border-width: 1.5px;">
                View Other Courses
            </button>
        </div>

    </div>
</template>

<style scoped>
.me_card{
    box-shadow: 0 2px 6px 0 rgba(0, 0, 0, 0.2), 0 4px 18px 0 rgba(0, 0, 0, 0.19);

}
</style>