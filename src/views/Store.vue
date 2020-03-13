<template>
  <div class="profile-page">
    <section class="section-store-cover section-shaped my-0">
      <div class="shape shape-store shape-set shape-skew alpha-4">
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
      </div>
    </section>
    <section class="section section-skew">
      <div class="container">
        <card shadow class="card-profile mt--300" no-body>
          <div class="px-4">
            <div class="product-container">
              <div class="row justify-content-center">
                <productcard />
                <productcard />
                <productcard />
                <productcard />
                <productcard />
              </div>
            </div>
          </div>
        </card>
      </div>
    </section>
  </div>
</template>
<script>
export default {};
</script>
<style>
.product-container{
    padding-bottom :50px;
}
</style>
