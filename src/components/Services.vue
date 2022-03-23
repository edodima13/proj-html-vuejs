<template>
    <div>
        <StartVue/>
        <div class="container-m">
            <div class="data-descriptions">
                <img src="../assets/img/Group-247.png" alt="">
                <h4>Data analysis</h4>
                <p>When, while the lovely valley teems with vapour around meand the meridian sun strikes the upper</p>
            </div>
            <div class="data-descriptions">
                <img src="../assets/img/Group-567.png" alt="">
                <h4>Data analysis</h4>
                <p>When, while the lovely valley teems with vapour around meand the meridian sun strikes the upper</p>
            </div>
            <div class="data-descriptions">
                <img src="../assets/img/Group-538.png" alt="">
                <h4>Data analysis</h4>
                <p>When, while the lovely valley teems with vapour around meand the meridian sun strikes the upper</p>
            </div>
            <div class="data-descriptions">
                <img src="../assets/img/Group-566.png" alt="">
                <h4>Data analysis</h4>
                <p>When, while the lovely valley teems with vapour around meand the meridian sun strikes the upper</p>
            </div>
        </div>
        
    </div>
</template>
<script>
import StartVue from './StartSections.vue'

export default{
    components:{StartVue},
    name: 'ServiceVue'
}

</script>
<style scoped>

.data-descriptions{
    max-width: 18%;
    display: flex;
    gap: 20px;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
}
img{
    width: 100px;
}
p{
    color: #606060;
    text-align: center;
}
.container-m{
    display: flex;
    justify-content: space-around;
    flex-grow: 1;
}
</style>