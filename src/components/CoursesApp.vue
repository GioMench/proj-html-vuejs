<script>
import CardApp from './CardApp.vue'

export default {
    name: 'CoursesApp',
    components:{
        CardApp
    },
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
    <div class="me_container">
        <!--title-->
        <h3 class="text-center  fw-semibold">
            Courses
        </h3>
        <div class="text-center fw-light text_grey" style=" font-size: 15px;">
            To keep up with the costantly rising standards of play
        </div>
        <!--courses-->
        <div class="row py-4">
            <!--component-->
            <CardApp v-for="course in courses" :course="course" />
        </div>
        <div class="text-center py-1">
            <!--btn-->
            <button type="button" class="btn btn-outline-dark px-4 py-2 fw-semibold"
                style="--bs-btn-padding-y: .25rem; --bs-btn-padding-x: .5rem; --bs-btn-font-size: .75rem;border-width: 1.5px;">
                View Other Courses
            </button>
        </div>
    </div>
</template>

<style scoped>
.me_container{
    padding-top: 55px ;
    padding-bottom: 30px;
}

</style>