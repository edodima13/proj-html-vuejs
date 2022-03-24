<template>
    <div class="container-fluid">
        <div class="services">
            <p>Price list</p>
            <h3><span>Our</span> pricing</h3>
            <p>When, while the lovely valley teems with vapour around meand the meridian sun strikes the upper surface.</p>
        </div>
        <PricesCards/>
        <PricesCards/>
        <PricesCards/>
    </div>
    
</template>
<script>
import PricesCards from './PricesCards.vue'

export default {
    components:{
        PricesCards
    },
    name: 'PriceVue'
}
</script>
<style scoped>
.container-fluid{
    background-color: #09154C;
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-bottom: 200px;
}
.services{
    text-align: center;
    max-width: 440px;
    display: flex;
    gap: 10px;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    padding-bottom: 80px;
    padding-top: 50px;
}
.services p:first-child{
    color: #B6246E;
}
.services p:last-child{
    color: #AAAAAA;
}
h3{
    font-size: 30px;
    font-weight: 500;
    text-transform: capitalize;
    color: white;
}
span{
    font-weight: 700;
}

</style>