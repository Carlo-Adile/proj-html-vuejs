<script>
export default {
  name: "AppFooter",
  data () {
    return {}
  }
}
</script>

<template>
  <div class="my_container_sm">
    <div class="row debug">
      <div class="col-4">
        <ul>
          <li>Address</li>
          <li>382</li>
          <li>+1</li>
          <li>support@</li>
          <li>icone</li>
        </ul>
      </div>
      <div class="col-2">
        <ul>
        <li>Explore</li>
        <li>li</li>
        <li>li</li>
        <li>li</li>
        <li>li</li>
        <li>li</li>
      </ul>
      </div>
      <div class="col-2">
        <ul>
        <li>Information</li>
        <li>li</li>
        <li>li</li>
        <li>li</li>
        <li>li</li>
      </ul>
      </div>
      <div class="col-4">
        <ul>
          <li>Instagram</li>
          <li></li>
        </ul>
      </div>
      <div class="col-12">
        @ 2020 Maxcoach inc
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
@import '../assets/scss/colors.scss';
@import '../assets/scss/structure.scss';

.debug {
  border: 1px dashed black;
}

.my_container_sm{
  @include mixin_container_sm;
  .row{
    height: 300px;
  }
}


</style>