<template>
  <div class="app">
    <!-- <nav-header></nav-header> -->
    <router-view></router-view>
    <!-- <nav-footer></nav-footer> -->
  </div>
</template>

<script>
// @ is an alias to /src
// import navHeader from '@/components/navHeader';
// import navFooter from '@/components/navFooter';
export default {
  name: 'App',
  components: {
    // navHeader,
    // navFooter
  }
}
</script>
<style lang="scss">
@import './assets/scss/reset.scss';
</style>