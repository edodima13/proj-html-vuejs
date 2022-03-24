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
                <li><span>Creative</span>designed enable</li>
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
        background-color: red;
    }
    .type-subscription{
        position: relative;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        gap: 10px;
        color: black;
    }
    h3{
        font-size: 30px;
    }
    .price{
        font-size: 60px;
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
    }
    .info{
        text-transform: uppercase;
        padding-bottom: 20px;
    }
    .benefit ul{
        display: flex;
        flex-direction: column;
        gap: 5px;
        color: white;
        align-items: center;
        justify-content: center;
    }
</style>
