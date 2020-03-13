<template>
    <section class="section-hero section-shaped my-0 img-set">
        <div class="shape shape-style-4 shape-set">
            <span class="span-150"></span>
            <span class="span-50"></span>
            <span class="span-50"></span>
            <span class="span-75"></span>
            <span class="span-100"></span>
            <span class="span-75"></span>
            <span class="span-50"></span>
            <span class="span-100"></span>
            <span class="span-50"></span>
            <span class="span-100"></span>
        </div>
        <div class="container shape-container d-flex align-items-center">
            <div class="col px-0">
                <div class="row justify-content-center align-items-center">
                    <div class="col text-center">
                        <img src="img/logo-2.png" style="width: 200px;" class="img-fluid">
                        <p class="lead text-white mt-4 mb-5">The Best Beef Jerky Around</p>
                        <div class="btn-wrapper">
                            <base-button tag="a"
                                         href="#/store"
                                         class="mb-3 mb-sm-0"
                                         type="info"
                                         icon="fa fa-shopping-cart">
                                Shop
                            </base-button>
                            <base-button tag="a"
                                         href="#"
                                         class="mb-3 mb-sm-0"
                                         type="white"
                                         icon="fa fa-question">
                                About Us
                            </base-button>
                        </div>
                    </div>
                    <!-- <div class="col-lg-8 text-center">
                        <img src="img/beef main.png" style="width: 400px;" class="img-fluid">
                    </div> -->
                </div>
            </div>
        </div>
    </section>
</template>
<script>
export default {};
</script>
<style>
.test1{
    background-color:green;
}
.test2{
    background-color:blue;
}
.img-set{

  background-image: url('../../../public/img/main-jerky.jpg');  
  background-position: center;
  background-size: cover;
  background-repeat: no-repeat;
  position: relative;
}

</style>
