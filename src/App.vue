<template>
  <div id="app">
    <!--COMPONENTE HEADER-->
    <HeaderVue/>
    <!--COMPONENTE MAIN-->
    <MainVue/>
    <!--COMPONENTE FOOTER-->
    <FooterVue/>
  </div>
</template>

<script>
import HeaderVue from './components/HeaderComponent.vue'
import MainVue from './components/MainComponent.vue'
import FooterVue from './components/FooterComponent.vue'


export default {
  name: 'App',
  components: {
    HeaderVue,
    MainVue,
    FooterVue
  },
}
</script>

<style lang="scss">
@import './assets/scss/mixins.scss';

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}


</style>
