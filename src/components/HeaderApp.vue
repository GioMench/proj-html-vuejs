<script>

export default{
    name: 'HeaderApp'
}
</script>

<template>

  <section class=" section_header">
    <!--navbar-->
    <div class="container-md d-flex justify-content-between p-4 text-light fw-light" style="height: 100%;">
        <!--left-side-navbar-->
        <div class="navbar_left d-flex flex-column justify-content-between"> 
            <!--address-academy-->
            <div>
                <span style="color: #FFCD18;"><i class="fa-solid fa-location-dot"></i></span>
                6767 Santa Monica Blvd,Los Angeles,CA 90038
            </div>
            <!--logo-academy-->
            <div>
                <img src="/public/images/mt-2236-home-logo.png" alt="">
            </div>
        </div>
        <!--right-side-navbar-->
        <div class="navbar_right">

            <div>
                <span>
                    numero
                </span>
                <span>
                    btn Donate
                </span>
            </div>

            <div>
                list dinamica
            </div>
        </div>


    </div>
  </section>
   


   
</template>

<style>
@import 'bootstrap/dist/css/bootstrap.css';
@import 'bootstrap-vue/dist/bootstrap-vue.css';
@import url('https://fonts.googleapis.com/css2?family=Alexandria:wght@100..900&display=swap');

.section_header{
    height: 130px;
    background-color: rgba(0, 0, 0, 0.431);
    z-index: 1;

}


</style>
