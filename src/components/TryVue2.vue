<template>
    <div class="container-fluid">
        <div class="container-l">
        <!--inserire due contenitori-->
        <!--lavorare sul primo contenitore e gestire il font-weight-->
        <!--generare il paragrafo con la mixins del font-size-->
        <!--generare due button con le stesse caratteristiche all'interno di un div-->
            <div class="thumb">
                <img src="../assets/img/nemoodar.png" alt="">
                <img src="../assets/img/men-data.png" alt="">
            </div>
            <div class="description">
                <p>start your project</p>
                <p class="fw-l">
                    grow your business <span class="fw-m">with our strategy</span>
                </p>
                <p class="sub-description">
                    When, while the lovely valley teems with vapour around meand the meridian sun strikes the upper surface. of the impenetrable follage of my trees, and but a few stray glearns steal into the inner sanctuary.
                </p>
                <div class="try-btn">
                    <button class="button-l">try it now</button>
                    <button class="button-l">Explore more</button>
                </div>
            </div>
        </div>
    </div>
    
</template>
<script>

export default {
    name: 'TryVue2'
}
</script>
<style scoped>
    .container-fluid{
        background-color: #09154C;
        margin: 0 auto;
        padding: 120px 0;
    }   
    .container-l{
        display: flex;
        align-items: center;
        justify-content: space-between;
    }
    .thumb{
        position: relative;
    }
    img{
        height: 300px;
        position: absolute;
        transform: translatey(-50%);
    }
    .thumb img:first-child{
        transform: translate(-10%, -70%);
        height: 250px;
    }
    .fw-l,.fw-m{
        font-size: 33px;
        text-transform: capitalize;
    }
    .fw-l{
        padding-bottom: 20px;
    }
    .description{
        max-width: 50%;
        padding-right: 100px;
    }
    .description p:first-child{
        text-transform: capitalize;
        padding-bottom: 20px;
    }
    .sub-description{
        padding-right: 70px;
        padding-bottom: 25px;
        color: #0A87BC;
    }
    .try-btn{
        display: flex;
        gap: 15px;
    }
    
</style>