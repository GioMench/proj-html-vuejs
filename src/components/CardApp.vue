<script>
export default{
    name:'CardApp',
    props : {
        course : Object
    }
}
</script>

<template>
<div class="col-4">
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
</template>

<style scoped></style>