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

  <HeaderPromo />
  <HeaderNavbar />

</template>

<style lang="scss" scoped>

</style>