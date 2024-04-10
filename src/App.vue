<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  name: "App",
  data() {
    return {

    }
  },
  components: {
    AppHeader,
    AppMain,
    AppFooter
  }
}
</script>

<template>
  <AppHeader />
  <AppMain />
  <AppFooter />
</template>

<style lang="scss" scoped>
@import '../src/assets/scss/colors.scss';
@import '../src/assets/scss/structure.scss';

* {
  padding: 0;
  margin: 0 auto;
}
</style>
