<template>
    <footer>
        <FlistVue 
            :linkList="fLinks" 
            v-for="(link, index) in fLinks" 
            :key="index"
            :info="link.info"/>
            <FlistsVue 
            :linksList="fLinkss" 
            v-for="(link, index) in fLinkss" 
            :key="index"
            :info="link.info"/>
    </footer>
</template>
<script>
import FlistVue from './FooterList.vue'
import FlistsVue from './FooterList2.vue'

export default{
    name: 'FooterVue',
    props: {
        linkList: Array,
        linksList: Array
    },
    components:{ FlistVue, FlistsVue },
    data(){
    return{
      fLinks:[
        {
          'info': 'Services'
        },
        {
          'info': 'Contact'
        },
        {
          'info': 'Blog'
        }
      ],
      fLinkss:[
        {
          'info': 'Art Design'
        },
        {
          'info': 'Computer'
        },
        {
          'info': 'It News'
        },
        {
          'info': 'Networking'
        },
        {
          'info': 'Web Security'
        }
      ]
    }
  }
}
</script>
<style scoped>
     
</style>