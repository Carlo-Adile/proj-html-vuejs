<script>
import HeaderPromo from './HeaderPromo.vue';
import HeaderNavbar from './HeaderNavbar.vue';


export default {
  name: "AppHeader",
  data() {
    return {}
  },
  components: {
    HeaderPromo,
    HeaderNavbar
  }
}
</script>

<template>
  <div class="container-sm">
    <div class="row">
      <div class="col-6">
        Hello World
      </div>
      <div class="col-2">
        Hi
      </div>

      <div class="col-6">
        <HeaderPromo />
      </div>

      <div class="col-6">
        <HeaderNavbar />
      </div>

    </div>
    

    
    
  </div>
</template>

<style lang="scss" scoped>
#my_row{
  display: flex;
  flex-wrap: wrap;
}

</style>