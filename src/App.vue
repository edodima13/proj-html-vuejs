<template>
  <div id="app">
    <HeaderVue/>
  </div>
</template>

<script>
import HeaderVue from './components/HeaderComponent.vue'

export default {
  name: 'App',
  components: {
    HeaderVue
  },
  data(){
    return{

    }
  }
}
</script>

<style lang="scss">
@import './assets/scss/app.scss';

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
