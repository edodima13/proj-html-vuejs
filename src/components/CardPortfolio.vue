<template>
    <div class="container-fluid">
        <div class="card-wrapper">
            <div class="card-image">
                <img src="../assets/img/work3.jpg" alt="">
            </div>
            <div class="card-info">
                <p>Mock-up</p>
                <p>Digital experience</p>
            </div>
        </div>
        <div class="card-wrapper">
            <div class="card-image">
                <img src="../assets/img/work1.jpg" alt="">
            </div>
            <div class="card-info">
                <p>Basket of Flower on table</p>
                <p>Branding strategy</p>
            </div>
        </div>
        <div class="card-wrapper">
            <div class="card-image">
                <img src="../assets/img/work2.jpg" alt="">
            </div>
            <div class="card-info">
                <p>Purinky products</p>
                <p>Digital experience</p>
            </div>
        </div>
        <div class="card-wrapper">
            <div class="card-image">
                <img src="../assets/img/work3.jpg" alt="">
            </div>
            <div class="card-info">
                <p>Satisy poster</p>
                <p>Branding strategy</p>
            </div>
        </div>
        <div class="card-wrapper">
            <div class="card-image">
                <img src="../assets/img/work3.jpg" alt="">
            </div>
            <div class="card-info">
                <p>Mock-up</p>
                <p>Digital experience</p>
            </div>
        </div>
    </div>
    
    
</template>
<script>

export default{
    name:'CardVue'
}
</script>
<style lang="scss" scoped>
@import '../assets/scss/mixins.scss';

    .container-fluid{
        display: flex;
        gap: 20px;
        transform: translateX(-277px);
        width: 1920px;
        padding-bottom: 70px;
    }
    .card-wrapper{
        width: 600px;
        background-color: white;
        border-radius: 20px;
        overflow: hidden;
    }
    .card-image img{  
        width: 100%;
        border-radius: 20px;
    }
    .card-info{
        padding: 20px 10px 20px 10px;
        display: flex;
        justify-content: space-between;
        color: black;
    }
    .card-info p:first-child{
        font-weight: 700;
        color: black;
        font-size: 13px;
    }
    .card-info p:last-child{
        color: grey;
    }
</style>