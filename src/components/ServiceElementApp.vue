<script>
export default {
    name: 'ServiceElementApp',
    props: {
        service: Object
    }
}
</script>

<template>

    <div class="col-6 gx-5 " style="padding-bottom: 35px;">
        <div>
            <!--icon-service-->
            <img class="icon_services" :src="'/public/images/' + service.img" alt="icon team">
        </div>
        <!--title-service-->
        <div class="fw-semibold text-capitalize py-1" style="font-size: 13px;">
            {{ service.title }}
        </div>
        <!--description-serice-->
        <p class="text_grey fw-light py-1" style="font-size: 11px;">
            {{ service.text }}
        </p>
    </div>

</template>

<style scoped>
.icon_services {
    width: 40px;
}
</style>