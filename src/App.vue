<template>
  <div id="app">
    <!--HEADER CON LOGO E LINKS DELLA PAGE-->
    <HeaderVue/>
    <!--COMPONENTE PER INIZIARE UN PROGETTO-->
    <MainVue/>
  </div>
</template>

<script>
import HeaderVue from './components/HeaderComponent.vue'
import MainVue from './components/MainComponent.vue'


export default {
  name: 'App',
  components: {
    HeaderVue,
    MainVue
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
