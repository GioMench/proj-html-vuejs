<script>
export default {
    name: 'ServiceApp',
    data() {
        return {
            skills: [
                'Build self-regulation and motivation',
                'Help with concentration issues',
                'Learn to plan, organize, and prioritize',
                'Regulate emotions',
                'Learn to pay attention to detail'
            ],

            
        }
    }
}
</script>



<template>
    <!--service-section-->
    <section class="me_container container py-5">
        <!--title-->
        <h3 class="text-center text-uppercase fw-semibold">
            our services
        </h3>
        <div class="text-center fw-light text_grey" style=" font-size: 15px;">
            We make your child happy day after day
        </div>
       
        <div class="row">
            <!--left-section-service-->
            <div class="col-4">
                <!--title-->
                <h6>
                    Chess Education
                </h6>
                <div class="text_grey fw-light" style="font-size: 14px;">
                    Popular education for your child and you
                </div>
                <!--explain-skill-->
                <p class="text_grey fw-light" style="font-size: 11px;">
                    Teachers and parents around the world know that chess is not a simple game. It is a great learning
                    tool that will help build your child's executive function skills.
                </p>
                <!--list-skills-->
                <ul>
                    <li v-for="skill in skills" class="text_grey fw-light items_skill" style="font-size: 11px;">
                        <span><img class="px-2" src="/public/images/mt-2236-home-icon-bullet.png" alt="chess game"
                                style="margin-left: -30px;"></span>
                        {{ skill }}
                    </li>
                </ul>
                <button type="button" class="btn px-4 py-2 fw-semibold bg_accent" style="--bs-btn-padding-y: .25rem; --bs-btn-padding-x: .5rem; --bs-btn-font-size: .75rem;">Learn More</button>


            </div>
            <!--right-section-service-->
            <div class="col-8">
                <div class="row ">
                    <div class="col-6 gx-5 ">
                        <div>
                            <img class="icon_services" src="/public/images/mt-2236-home-icon1.png" alt="icon team" >
                        </div>
                        <div class="fw-semibold text-capitalize" style="font-size: 13px;">
                            various age groups
                        </div>
                        <p class="text_grey fw-light" style="font-size: 11px;" >
                            We provide chess classes to both children from 5 years old and adult.
                        </p>
                    </div>
                    <div class="col-6 gx-5 ">
                        <div>
                            <img class="icon_services" src="/public/images/mt-2236-home-icon2.png" alt="icon team" >
                        </div>
                        <div class="fw-semibold text-capitalize" style="font-size: 13px;">
                            top chess variants
                        </div>
                        <p class="text_grey fw-light" style="font-size: 11px;" >
                            We don't only teach classical chess but also other top variants of this game.
                        </p>
                    </div>
                    <div class="col-6 gx-5 gy-4">
                        <div>
                            <img class="icon_services" src="/public/images/mt-2236-home-icon3.png" alt="icon team" >
                        </div>
                        <div class="fw-semibold text-capitalize" style="font-size: 13px;">
                            best chess players
                        </div>
                        <p class="text_grey fw-light" style="font-size: 11px;" >
                            Our alumni have won many prestigious chess tournaments in the country.
                        </p>
                    </div>
                    <div class="col-6 gx-5 gy-4">
                        <div>
                            <img class="icon_services text-capitalize" src="/public/images/mt-2236-home-icon4.png" alt="icon team" >
                        </div>
                        <div class="fw-semibold" style="font-size: 13px;">
                           best chess openings
                        </div>
                        <p class="text_grey fw-light" style="font-size: 11px;" >
                            Our students know all the best chess openings and how to use them.
                        </p>
                    </div>
                    
                </div>
            </div>
        </div>

    </section>





</template>

<style scoped>
.icon_services{
    width: 40px;
}
</style>