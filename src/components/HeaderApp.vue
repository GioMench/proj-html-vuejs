<script>
import LinksHeaderApp from './LinksHeaderApp.vue'
export default{
    name: 'HeaderApp',
    components:{
        LinksHeaderApp
    },
    data(){
        return{
            infoList:['home','service', 'courses', 'about', 'FAQ', 'blog', 'contact us']
        }
    }
}
</script>

<template>
    <!--header-section-->
  <section class="section_header">
    <!--navbar-->
    <div class="me_container d-flex justify-content-between p-3 text-light fw-light" style="height: 100%;">
        <!--left-side-navbar-->
        <div class="navbar_left d-flex flex-column justify-content-between"> 
            <!--address-academy-->
            <div>
                <span><i class="fa-solid fa-location-dot text_accent"></i></span>
                6767 Santa Monica Blvd,Los Angeles,CA 90038
            </div>
            <!--logo-academy-->
            <div>
                <img src="/public/images/mt-2236-home-logo.png" alt="" style="width: 135px;">
            </div>
        </div>
        <!--right-side-navbar-->
        <div class="navbar_right d-flex flex-column justify-content-between">

            <div>
                <!--phone-number-academy-->
                <span>
                    <i class="fa-solid fa-phone text_accent"></i>
                    Call Now 123-456-7890
                </span>
                <!--btn-->
                <span class="align-self-end">
                    <button type="button" class="btn btn-light py-1 fw-medium" style="margin-left: 130px;--bs-btn-padding-y: .25rem; --bs-btn-padding-x: .5rem; --bs-btn-font-size: .75rem; width: 120px;border-radius: 8px;">Donate</button>
                </span>
            </div>

            <div>
                <!--link-info-->
                <ul class="d-flex m-0" >
                    <!--component-->
                    <LinksHeaderApp v-for="info in infoList" :info="info" />
                </ul>
            </div>
        </div>


    </div>
  </section>
   


   
</template>

<style scoped>
.section_header{
    height: 85px;
    background-color:#00030f65 ;
    z-index: 2;
   position: relative;
   font-size: 11px;
}


</style>
