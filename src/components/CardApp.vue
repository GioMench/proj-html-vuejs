<script>
export default {
    name: 'CardApp',
    props: {
        course: Object
    }
}
</script>

<template>
    <div class="col-4">
        <div class="card me_card">
            <!--img-->
            <img :src="'/public/images/' + course.img" alt="" style="width: 100%;">
            <div class="card-body text-center py-4">
                <!--title-->
                <h6 class="card-title text-capitalize fw-semibold">
                    {{ course.title }}
                </h6>
                <!--text-->
                <p class="card-text fw-light px-2 text_grey" style="font-size: 11.5px;">
                    {{ course.text }}
                </p>
                <!--price-->
                <h6 class="card-title fw-semibold">
                    {{ course.price }}
                </h6>
                <!--btn-->
                <button type="button" class="btn px-4 py-2 fw-semibold bg_accent"
                    style="--bs-btn-padding-y: .25rem; --bs-btn-padding-x: .5rem; --bs-btn-font-size: .75rem;">View
                    More</button>
            </div>
        </div>
    </div>
</template>

<style scoped>
.me_card {
    box-shadow: 0 2px 6px 0 rgba(0, 0, 0, 0.2), 0 4px 18px 0 rgba(0, 0, 0, 0.19);
    border-radius: 0;

}
</style>