<template>
    <div class="card-wrapper">
        <div class="type-subscription">
            <h3>Designing</h3>
            <p class="info">process</p>
            <span class="price fw-l">40</span>
            <p class="time">per month</p>
        </div>
        <div class="benefit">
            <ul>
                <li><span>Creative</span> designed enable</li>
                <li><span>Vibrant</span> color usage</li>
                <li><span>eye</span> catching design</li>
                <li><span>extreme</span> typography</li>
                <li><span>exceptional</span> design</li>
            </ul>
        </div>
    </div>
</template>
<script>


export default {
    name: 'PricesCards'
}
</script>
<style scoped>
    .card-wrapper{
        width: 30%;
        border-radius: 15px;
        background-color: white;
    }
    .type-subscription{
        position: relative;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        gap: 10px;
        color: black;
        padding: 20px 0;
    }
    h3{
        font-size: 30px;
        z-index: 999;
    }
    .price{
        font-size: 60px;
        z-index: 1;
    }
    .price::before{
        display: block;
        content: '$';
        font-size: 11px;
        color: black;
       
    }
    .price::after{
        display: block;
        content: '60';
        position: absolute;
        top: -74px;
        right: -6px;
        font-size: 200px;
        opacity: 0.2;
        color: #AAAAAA;
        z-index: -1;
    }
    .info{
        text-transform: uppercase;
        padding-bottom: 20px;
        z-index: 99;
        color: black;
    }
    .benefit{
        padding-top: 20px;
        padding-bottom: 40px;
    }
    .benefit ul{
        display: flex;
        flex-direction: column;
        gap: 10px;
        color: rgba(0, 0, 0, 0.5);
        align-items: center;
        justify-content: center;
        text-transform: capitalize;
        font-size: 13px;
    }
    .benefit ul span{
        color: black;
    }
</style>
