<script>

export default{
    name: 'HeaderApp',
    data(){
        return{
            infoList:['Service', 'Courses', 'About', 'FAQ', 'Blog', 'Contact Us']
        }
    }
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
        <div class="navbar_right d-flex flex-column justify-content-between">

            <div>
                <span>
                    <i class="fa-solid fa-phone"style="color: #FFCD18;"></i>
                    Call Now 123-456-7890
                </span>
                <span class="align-self-end">
                    <button type="button" class="btn btn-light px-5 py-1 fw-medium" style="margin-left: 125px;">Donate</button>
                </span>
            </div>

            <div>
                <ul class="d-flex m-0" >
                    <li  class="px-2" style="color: #FFCD18;">
                        Home
                    </li>
                    <li class="px-2 " v-for="info in infoList">
                        {{ info }}
                    </li>
                </ul>
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
