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

  <section class="section_header">
    <!--navbar-->
    <div class="me_container d-flex justify-content-between p-1 text-light fw-light" style="height: 100%;">
        <!--left-side-navbar-->
        <div class="navbar_left d-flex flex-column justify-content-between"> 
            <!--address-academy-->
            <div>
                <span><i class="fa-solid fa-location-dot text_accent"></i></span>
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
                    <i class="fa-solid fa-phone text_accent"></i>
                    Call Now 123-456-7890
                </span>
                <span class="align-self-end">
                    <button type="button" class="btn btn-light px-5 py-1 fw-medium" style="margin-left: 130px;--bs-btn-padding-y: .25rem; --bs-btn-padding-x: .5rem; --bs-btn-font-size: .75rem;">Donate</button>
                </span>
            </div>

            <div>
                <ul class="d-flex m-0" >
                    <li  class="px-2 text_accent">
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

<style scoped>
.section_header{
    height: 80px;
    background-color: rgba(0, 0, 0, 0.406);
    z-index: 2;
   position: relative;
   font-size: 12px;

}


</style>
