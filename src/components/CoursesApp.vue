<script>


export default {
    name: 'CoursesApp',
    data() {
        return {
            courses: [
                {
                    img: "mt-2236-home-img1.jpg",
                    title: "garry kasparov's masterclass",
                    text: "Learn the tips, tricks, and stategies from one of the best masters",
                    price: " $456"

                },
                {
                    img: "mt-2236-home-img2.jpg",
                    title: "online chess lessons for beginners",
                    text: "Catered to adult beginners who have a few hours a week to practise",
                    price: " $205"

                },
                {
                    img: "mt-2236-home-img3.jpg",
                    title: "international chess school online",
                    text: "Chess lessons for children and adults held completely online",
                    price: " $356"

                }
            ]
        }
    }

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
            <div class="col-4" v-for="course in courses">
                <div class="card me_card">
                    <img :src="'/public/images/' + course.img" alt="" style="width: 100%;">
                    <div class="card-body text-center py-4">
                        <h6 class="card-title text-capitalize fw-semibold">
                            {{ course.title }}
                        </h6>
                        <p class="card-text fw-light px-2 text_grey" style="font-size: 11.5px;">
                            {{ course.text }}
                        </p>
                        <h6 class="card-title fw-semibold">
                            {{ course.price }}
                        </h6>
                        <button type="button" class="btn px-4 py-2 fw-semibold bg_accent"
                            style="--bs-btn-padding-y: .25rem; --bs-btn-padding-x: .5rem; --bs-btn-font-size: .75rem;">View
                            More</button>
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
.me_card {
    box-shadow: 0 2px 6px 0 rgba(0, 0, 0, 0.2), 0 4px 18px 0 rgba(0, 0, 0, 0.19);

}
</style>