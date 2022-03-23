<template>
    <div class="container-fluid">
        <div class="container-l">
        <!--inserire due contenitori-->
        <!--lavorare sul primo contenitore e gestire il font-weight-->
        <!--generare il paragrafo con la mixins del font-size-->
        <!--generare due button con le stesse caratteristiche all'interno di un div-->
            <div class="description">
                <p class="fw-l">
                    Business planning <span class="fw-m">digital tecnhology</span> modern solutions!
                </p>
                <p class="sub-description">
                    When, while the lovely valley teems with vapour around meand the meridian sun strikes the upper surface.
                </p>
                <div>
                    <button></button>
                    <button></button>
                </div>
            </div>
            <div>

            </div>
        </div>
    </div>
    
</template>
<script>

export default {
    name: 'TryVue'
}
</script>
<style scoped>
    .container-fluid{
        background-color: #09154C;
        margin: 0 auto;
    }
    .container-l{
        display: flex;
        align-items: center;
        justify-content: space-between;
    }
    .fw-l,.fw-m{
        font-size: 45px;
        text-transform: capitalize;
    }
    .description{
        max-width: 50%;
    }
    .sub-description{
        padding-right: 150px;
    }
</style>