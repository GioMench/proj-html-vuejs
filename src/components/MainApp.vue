<script>
export default {
    name: 'MainApp'
}
</script>

<template>

    <!--back-img-welcome-section-->
    <img class=" img_top" src="/public/images/mt-2236-home-bg1.jpg" alt="">
    <!--welcome-section-->
    <div class="container-fluid welcome_section">
        <span class="align-middle">
            <i class="fa-solid fa-phone" style="color: #FFCD18;"></i>
        </span>

        <div class="me_container ">
            <span>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Amet id nostrum quidem at animi soluta nisi,
                alias,
                iure temporibus nemo perferendis vel ipsam delectus? Hic earum repellendus veniam! Assumenda,
                perspiciatis.
            </span>
        </div>
    </div>
    



</template>

<style scoped>
@import 'bootstrap/dist/css/bootstrap.css';
@import 'bootstrap-vue/dist/bootstrap-vue.css';
@import url('https://fonts.googleapis.com/css2?family=Alexandria:wght@100..900&display=swap');

.img_top {
    max-width: 100%;
    height: 100%;
    position: absolute;
    top: 0;
    z-index: -1;
}

.welcome_section {
    z-index: 3;
    height: 460px;
    position: relative;
}

.fa-phone {
    font-size: 25px;
    background-color: #FFFFFF;
    padding: 10px;
    border-radius: 50%;
    margin-left: 0;
    position: absolute;
    top: 50%;
}
</style>