<script>
import HeaderPromo from './HeaderPromo.vue';
import HeaderNavbar from './HeaderNavbar.vue';


export default {
  name: "AppHeader",
  data () {
    return {}
  },
  components: {
    HeaderPromo,
    HeaderNavbar
  }
}
</script>

<template>
  <div>
    Hello World

    <HeaderPromo />
    <HeaderNavbar />
  </div>
</template>

<style lang="scss" scoped>

</style>