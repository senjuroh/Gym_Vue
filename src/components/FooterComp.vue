<template>
  <div class="footer">
    <div class="container my-5">
      <div class="row d-flex justify-content-between">
        <div class="col-md-3">
          <div class="head1 fs-4 text-start">Gym Management System</div>
          <a href="">About Us</a><br />
          <a href="">Our Services</a>
        </div>
        <div class="col-md-3">
          <div class="head1 fs-4">GET HELP</div>
          <a href="">How to Order?</a><br />
          <a href="">FAQs</a><br />
          <a href="">Our Services</a>
        </div>
        <div class="col-md-3">
          <div class="head1 fs-4">CALL US</div>
          <a href=""><i class="fa-solid fa-location-dot"></i> Dharan</a><br />
          <a href=""><i class="fa-solid fa-phone"></i> 98373473823</a><br />
          <a href=""><i class="fa-solid fa-envelope"></i> jbmart@gmail.com</a>
        </div>
        <div class="col-md-3">
          <div class="head1 fs-4">DOWNLOAD APP</div>
          <a href=""
            ><img
              src="https://codeitapps.com/frontend/google.png"
              width="90px"
              height="30px"
              alt=""
          /></a>
          <a href="">
            <img
              src="https://codeitapps.com/frontend/apple.png"
              width="90px"
              height="30px"
              alt=""
          /></a>
          <div class="head1">CONNECT WITH US</div>
          <div class="awe-fonts">
            <i class="fa-brands fa-twitter me-3"></i>
            <i class="fa-brands fa-youtube me-3"></i>
            <i class="fa-brands fa-instagram me-3"></i>
            <i class="fa-brands fa-facebook me-3"></i>
          </div>
        </div>
      </div>
    </div>
    <div class="container">
      <div class="row d-flex justify-content-between align-items-center">
        <div class="col-md-6">
          <a href="#">Terms and Conditions </a> |
          <a href="#">Privacy Policy </a>
        </div>
        <div class="col-md-6 d-flex justify-content-end">
          <a href="#">© 2020 JB Mart Pvt. Ltd. All Rights Reserved</a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "FooterComp",
};
</script>

<style>
.awe-fonts i {
  font-size: 25px;
  color: gray;
}
</style>