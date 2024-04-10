<script>
export default {
  name: "AppFooter",
  data() {
    return {}
  }
}
</script>

<template>
  <div class="my_container_md my-4 py-4">
    <div class="row debug">
      <div class="col-4">
        <ul>
          <li>
            <h5>Address</h5>
          </li>
          <li>
            <p>382 NE 191st St # 87394 Miami, FL 33179-3899</p>
          </li>
          <li>
            <p>+1 (305) 547-9909 (9am - 5pm EST, Monday - Friday)</p>
          </li>
          <li>
            <p>support@maxcoach.com</p>
          </li>
          <li class="d-flex gap-4">
            <i class="fa-brands fa-square-facebook"></i>
            <i class="fa-brands fa-twitter"></i>
            <i class="fa-brands fa-instagram"></i>
            <i class="fa-brands fa-linkedin"></i>
          </li>
        </ul>
      </div>
      <div class="col-2">
        <ul>
          <li>
            <h5>Explore</h5>
          </li>
          <li>
            <p>Start here</p>
          </li>
          <li>
            <p>Success story</p>
          </li>
          <li>
            <p>Blog</p>
          </li>
          <li>
            <p>Courses</p>
          </li>
          <li>
            <p>Contact us</p>
          </li>
        </ul>
      </div>
      <div class="col-2">
        <ul>
          <li>
            <h5>Information</h5>
          </li>
          <li>
            <p>Membership</p>
          </li>
          <li>
            <p>Purchase guide</p>
          </li>
          <li>
            <p>Privacy policy</p>
          </li>
          <li>
            <p>Terms of services</p>
          </li>
        </ul>
      </div>
      <div class="col-4">
        <ul>
          <li>
            <h5 style="display: inline-flex">Instagram</h5>
            <span> @maxcoach</span>
          </li>
          <li>
            <div class="row">
              <div class="col-4">
                <img src="../assets/images/120084500_197897808368764_8114555493043279565_n.jpg" alt="">
              </div>
              <div class="col-4">
                <img src="../assets/images/120012142_177596140500760_8623485824101406058_n.jpg" alt="">
              </div>
              <div class="col-4">
                <img src="../assets/images/120099363_364334431619755_7198812647386067017_n.jpg" alt="">
              </div>
            </div>
          </li>
        </ul>
      </div>
      <div class="col-12">
        <p style="text-align: center;">@ 2020 Maxcoach. All Rights Reserved</p>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
@import '../assets/scss/colors.scss';
@import '../assets/scss/structure.scss';
@import '../assets/scss/font.scss';
@import '../assets/scss/variables.scss';

* {
  @include various;
}

/* .debug {
  border: 1px dashed black;
} */

.my_container_md {
  @include mixin_container_md;

  .row {
    height: 250px;
  }
  h5 {
    padding-bottom: 0.5rem;
  }
  p {
    font-size: 0.9rem;
    line-height: 1rem;
    color: $regular;
  }
  img {
    width: 100%;
    height: auto;
  }
  i{
    font-size: 1.5rem;
    color: $lighter;
  }
}
</style>