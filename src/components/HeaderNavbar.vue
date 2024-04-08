<script>
export default {
  name: "HeaderNavbar",
  data() {
    return {}
  }
}
</script>

<template>
  <nav class="navbar navbar-expand-lg p-0 debug">
    <div class="my_container_lg">
      <div class="row align-items-center">
        <!-- navbar brand -->
      <div class="col-1">
        <a href="#" class="navbar-brand">Navbar</a>
      </div>

      <!-- dropdown menu -->
      <div class="col-6">
        <ul class="navbar-nav">
          <li class="nav-item dropdown">
            <a href="" class="nav-link dropdown-toggle">Home</a>
          </li>
          <li class="nav-item dropdown">
            <a href="" class="nav-link dropdown-toggle">Pages</a>
          </li>
          <li class="nav-item dropdown">
            <a href="" class="nav-link dropdown-toggle">Courses</a>
          </li>
          <li class="nav-item dropdown">
            <a href="" class="nav-link dropdown-toggle">Features</a>
          </li>
          <li class="nav-item dropdown">
            <a href="" class="nav-link dropdown-toggle">Blog</a>
          </li>
          <li class="nav-item dropdown">
            <a href="" class="nav-link dropdown-toggle">Shop</a>
          </li>
        </ul>
      </div>

      <!-- social icons -->
      <div class="col-1">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a href="#" class="nav-link">
              <i class="fa-brands fa-twitter"></i>
            </a>
          </li>
          <li class="nav-item">
            <a href="#" class="nav-link">
              <i class="fa-brands fa-facebook-f"></i>
            </a>
          </li>
          <li class="nav-item">
            <a href="#" class="nav-link">
              <i class="fa-brands fa-instagram"></i>
            </a>
          </li>
          <li class="nav-item">
            <a href="#" class="nav-link">
              <i class="fa-brands fa-linkedin"></i>
            </a>
          </li>
        </ul>
      </div>
      </div>

    </div>
  </nav>
</template>

<style lang="scss" scoped>
* {
  margin: 0 auto;
  text-align: center;
}

.debug {
  border: 1px dashed black;
}

.my_container_lg {
  width: 80%;
  margin: 0 auto;
  padding-right: 15px;
  padding-left: 15px;

  .row{
    height: 60px;
  }
}
</style>