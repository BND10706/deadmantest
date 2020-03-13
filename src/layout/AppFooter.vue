<template>
  <footer class="footer has-cards">
    <div class="container">
      <div class="row row-grid align-items-center my-md">
        <div class="col-lg-6">
          <h3 class="text-footer font-weight-light mb-2">
            Thank you for supporting us!
          </h3>
          <h4 class="mb-0 font-weight-light">
            Let's get in touch on any of these platforms.
          </h4>
        </div>
        <div class="col-lg-6 text-lg-center btn-wrapper">
          <a
            target="_blank"
            rel="noopener"
            href="#"
            class="btn btn-neutral btn-icon-only btn-twitter btn-round btn-lg"
            data-toggle="tooltip"
            data-original-title="Follow us"
          >
            <i class="fa fa-twitter"></i>
          </a>
          <a
            target="_blank"
            rel="noopener"
            href="#"
            class="btn btn-neutral btn-icon-only btn-facebook btn-round btn-lg"
            data-toggle="tooltip"
            data-original-title="Like us"
          >
            <i class="fa fa-facebook-square"></i>
          </a>
          <a
            target="_blank"
            rel="noopener"
            href="#"
            class="btn btn-neutral btn-icon-only btn-instagram btn-round btn-lg"
            data-toggle="tooltip"
            data-original-title="Like us"
          >
            <i class="fa fa-instagram"></i>
          </a>
        </div>
      </div>
      <hr />
      <div class="row align-items-center justify-content-md-between">
        <div class="col-md-6">
          <div class="copyright">
            &copy; {{ year }}
            Deadman Jerky Co.
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>
<script>
export default {
  name: "app-footer",
  data() {
    return {
      year: new Date().getFullYear()
    };
  }
};
</script>
<style>

</style>
