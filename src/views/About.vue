<template>
    <div>
        <section class="section section-shaped my-0 overflow-hidden">
              <div class="shape shape-style-3 bg-gradient-default">
            </div>
            <div class="container">
                
            </div>
            <div class="container">
                <div class="row justify-content-center text-center mb-lg">
                    <div class="col-lg-8">
                        <h2 class="display-3">About Us</h2>
                        <p class="lead text-muted">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec imperdiet ultricies lorem, a volutpat nulla imperdiet at. Curabitur mi massa, hendrerit dignissim scelerisque et, lacinia eget dolor. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec pretium non mauris in vehicula. Curabitur faucibus leo tortor, nec pellentesque ligula pulvinar vitae. Etiam fermentum est ut sapien euismod, in auctor magna vehicula. Sed lacinia bibendum elit sit amet porta. Nullam scelerisque efficitur aliquet. Aenean consectetur est hendrerit nisl molestie volutpat. Fusce pellentesque urna vitae augue imperdiet maximus. Vivamus ultricies convallis molestie. Proin id laoreet augue. Proin nisl diam, iaculis placerat libero vel, hendrerit dictum diam.</p>
                    </div>
                </div>
                <div class="row">
                    <div class="col-lg">
                        <div class="px-4 tex-center">
                            <img v-lazy="'img/theme/team-1-800x800.jpg'"
                                 class="rounded-circle img-center img-fluid shadow shadow-lg--hover"
                                 style="width: 200px;">
                            <div class="pt-4 text-center">
                                <h5 class="title">
                                    <span class="d-block mb-1 text-muted">Chase Deadman</span>
                                    <small class="h6 text-muted">Owner</small>
                                </h5>
                                <div class="mt-3">
                                    <base-button tag="a" href="#" type="success" icon="fa fa-twitter" rounded
                                                 icon-only></base-button>
                                    <base-button tag="a" href="#" type="success" icon="fa fa-facebook" rounded
                                                 icon-only></base-button>
                                    <base-button tag="a" href="#" type="success" icon="fa fa-dribbble" rounded
                                                 icon-only></base-button>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section class="section section-shaped my-0 overflow-hidden">
            <div class="shape shape-style-3 bg-gradient-default shape-skew">
                <span></span>
                <span></span>
                <span></span>
                <span></span>
            </div>
            <div class="container pb-200">
                
            </div>
        </section>
        <section class="section section-lg pt-lg-0 section-contact-us">
            <div class="container">
                <div class="row justify-content-center mt--300">
                    <div class="col-lg-8">
                        <card gradient="secondary" shadow body-classes="p-lg-5">
                            <h4 class="mb-1">Contact us?</h4>
                            <p class="mt-0">Your voice is very important to us.</p>
                            <base-input class="mt-5"
                                        alternative
                                        placeholder="Your name"
                                        addon-left-icon="ni ni-user-run">
                            </base-input>
                            <base-input alternative
                                        placeholder="Email address"
                                        addon-left-icon="ni ni-email-83">
                            </base-input>
                            <base-input class="mb-4">
                                    <textarea class="form-control form-control-alternative" name="name" rows="4"
                                              cols="80" placeholder="Type a message..."></textarea>
                            </base-input>
                            <base-button type="default" round block size="lg">
                                Send Message
                            </base-button>
                        </card>
                    </div>
                </div>
            </div>
        </section>

    </div>
</template>
<script>
export default {};
</script>
<style>
</style>
