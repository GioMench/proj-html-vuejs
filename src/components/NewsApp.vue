<script>
export default {
    name: 'NewsApp'
}
</script>

<template>
    <!--news-section-->
    <section class="bg_light">
        <div class="me_container py-5">
            <div class="row">
                <div class="col-4">
                    <h3 class=" text-capitalize fw-semibold">
                        latest news
                    </h3>
                    <div class="py-2" style="border-bottom: 3px #FFCD18 solid; width: 60px;"></div>
                    <div class="py-4">
                        <button type="button" class="btn btn-outline-dark px-4 py-2 fw-semibold"
                            style="--bs-btn-padding-y: .25rem; --bs-btn-padding-x: .5rem; --bs-btn-font-size: .75rem;border-width: 1.5px;">
                            View Other Posts
                        </button>
                    </div>
                </div>
                <div class="col-4">
                    <img src="/public/images/mt-2236-blog-img1.jpg" alt="" style="width: 100%;">
                    <div class="py-2" style="font-size: 12px;">
                        The most common mistakes when managing personal finances
                    </div>
                </div>
                <div class="col-4">
                    <img src="/public/images/mt-2236-blog-img2.jpg" alt="" style="width: 100%;">
                    <div class="py-2" style="font-size: 12px;">
                        Methods of the recruitment
                    </div>
                </div>
            </div>
        </div>

    </section>
</template>

<style scoped></style>