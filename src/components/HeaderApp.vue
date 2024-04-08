<script>

export default{
    name: 'HeaderApp'
}
</script>

<template>

  <section class=" section_header">
    <!--navbar-->
    <div class="container-md d-flex justify-content-between p-3">
        <!--left-side-navbar-->
        <div class="navbar_left"> 
            <div>
                via
            </div>
            <div>
                logo
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
    height: 180px;
    background-color: rgba(0, 0, 0, 0.431);
    z-index: 1;

}


</style>
