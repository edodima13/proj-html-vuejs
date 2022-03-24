<template>
    <footer>
      <div class="container-l">
        <div class="logo-footer">
          <img src="../assets/img/white-logo-2.png" alt="">
          <p>When, while lovely valley teems vapour aroundmeand meridian sun strikes the upper impenetrable</p>
        </div>
        <div>
          <h4>Quick links</h4>
          <FlistVue 
            :linkList="fLinks" 
            v-for="(link, index) in fLinks" 
            :key="index"
            :info="link.info"/>
        </div>
        <div>
          <h4>Resources</h4>
          <FlistsVue 
            :linksList="fLinkss" 
            v-for="(link, index) in fLinkss" 
            :key="index"
            :info="link.info"/>
        </div>
        <div class="contact">
          <h4>Contact us</h4> 
          <div>
            <p>
              <span>Address:</span>
              Patricla c. amedee 4401 waldeck street grapevine nashville, tx 76051
            </p>
          </div>
          <div>
            <p>
              <span>Phone:</span>
              +99 (0) 101 0000 888
            </p>
            <p>
              <span>Mail:</span>
              info@yourdomain.com
            </p>
          </div>
        </div>
      </div>
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
  footer{
    background-color: #09154C;
  }
  .container-l{
    display: flex;
    justify-content: space-between;
    padding: 100px 0;
  }
  .container-l > div{
    width: 20%;
  }
  .logo-footer img{
    padding-bottom: 30px;
    width: 100px;
  }
  .contact > div{
    padding-bottom: 10px;
  }
  h4{
    color: white;
    padding-bottom: 20px;
    padding-top: 10px;
  }
  footer p{
    color: #AAAAAA;
  }
  p span{
    color: white;
  }
</style>