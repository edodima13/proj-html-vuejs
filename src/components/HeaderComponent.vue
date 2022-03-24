<template>
    <header>
    <!--inserire testo dentro un container-l-->
        <div class="container-l">
        <!--PRIMA PARTE HEADER-->
            <!--inserire il logo-->
            <div class="logo">
                <img src="../assets/img/white-logo-2.png" alt="">
            </div>
            <div class="container">
                <!--creare la lista dei link dinamicamente in un altro componente-->
                <div class="container-s">
                  <HlistVue 
                    :linkList="hLinks" 
                    v-for="(link, index) in hLinks" 
                    :key="index"
                    :info="link.info"/>
                </div>
                <div>
                   <!--inserire il button per il log in-->
                    <div class="Sign-btn">
                        <button>Sign in</button>
                    </div>
                </div>
            </div>
        </div>
    
    </header>
    
</template>
<script>
import HlistVue from './HeaderList.vue'

export default{
    name: 'HeaderVue',
    props: {
        linkList: Array,
    },
    components:{
        HlistVue
    },
    data(){
    return{
      hLinks:[
        {
          'info': 'Home'
        },
        {
          'info': 'About'
        },
        {
          'info': 'Services'
        },
        {
          'info': 'Blog'
        },
        {
          'info': 'Contact'
        },
        {
          'info': 'Portfolio'
        },
      ]
    }
  }
}
</script>
<style lang="scss" scoped>
@import '../assets/scss/mixins.scss';
  

    header{
        background-color: #09154C;
        
    }
    .container-l{
        margin: 0 auto;
        display: flex;
        justify-content: space-between;
    }
    .logo{
        padding: 20px 0;
    }
    .container{
        display: flex;
        align-items: center;
        gap: 30px;
    }
    .container-s{
      display: flex;
      gap: 15px;
    }
    button{
      background-color: #03A7D3E6;
    }
</style>
