<script>
export default {
  name: "HeaderPromo",
  data() {
    return {}
  }
}
</script>

<template>

  <div id="my_header_promo">
    <div class="my_container_sm debug">
      <div class="row align-items-center">
        <!-- caption -->
        <div class="col-6">
          <p>Starts TOMORROW Our biggest event of the year...</p>
        </div>
        <!-- clock -->
        <div class="col-3">
          <i class="fa-regular fa-clock"></i>
          <span> 00 : 00 : 00 : 00</span>
        </div>
        <div class="col-3">
          <a class="btn btn-primary" href="#" role="button">Get ticket</a>
        </div>
      </div>

    </div>
  </div>

</template>

<style lang="scss" scoped>
@import '../assets/scss/colors.scss';
@import '../assets/scss/structure.scss';

* {
  margin: 0 auto;
  text-align: center;
  background-color: $secondary;
}

.debug {
  border: 1px dashed black;
}

#my_header_promo{
  width: 100%;
  background-color: $secondary;
}

.my_container_sm {
  @include mixin_container_sm;

  .row {
    height: 40px;
  }
}
</style>