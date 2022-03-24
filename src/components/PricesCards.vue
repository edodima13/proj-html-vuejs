<template>
    <div class="card-wrapper">
        <div class="type-subscription">
            <h3>Designing</h3>
            <p class="info">process</p>
            <span class="price fw-l">40</span>
            <p class="time">per month</p>
        </div>
        <div class="benefit">

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
    .info{
        text-transform: uppercase;
        padding-bottom: 20px;
    }
</style>
