<template>
    <div class="portfolio">
        <div class="container-l">
            <div class="services">
                <p>Portfolio</p>
                <h3><span>latest</span> work </h3>
            </div>
        </div>
        <CardVue/>
        <div class="div-dot-wrapper">
            <div class="div-dot red">
            </div>
            <div class="div-dot">
            </div>
            <div class="div-dot">
            </div>
            <div class="div-dot">
            </div>
            <div class="div-dot">
            </div>
        </div>
        
    </div>
    
    
    
</template>
<script>
import CardVue from './CardPortfolio.vue'

export default{
    components:{ CardVue },
    name: 'PortfolioVue'
}
</script>
<style scoped>
.portfolio{
    background-color: #FFFFFF80;
    padding-bottom: 10px;
}
.services{
    padding: 60px 0 40px;
}
.services p{
    color: #F9636B;
    padding-bottom: 10px;
}
h3{
    font-size: 30px;
    font-weight: 500;
}
span{
    font-weight: 700;
}
.div-dot{
    background-color: #00000025;
    border-radius: 999px;
    width: 5px;
    height: 5px;
    margin-bottom: 20px;
}
.div-dot-wrapper{
    display: flex;
    gap: 5px;
    justify-content: center;
}
.div-dot-wrapper .red{
    background-color: red;
}
</style>