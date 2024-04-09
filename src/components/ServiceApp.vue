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
            ]
        }
    }
}
</script>



<template>
    <!--service-section-->
    <section class="me_container container">
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


            </div>
            <!--right-section-service-->
            <div class="col-8">
                <div class="row">
                    <div class="col-6">
                        lorem
                    </div>
                    <div class="col-6">
                        lorem
                    </div>
                    <div class="col-6">
                        lorem
                    </div>
                    <div class="col-6">
                        lorem
                    </div>
                </div>
            </div>
        </div>

    </section>





</template>

<style scoped></style>