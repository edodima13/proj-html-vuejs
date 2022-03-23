<template>
    <div class="services">
        <p>Our services</p>
        <h3><span>What</span> we do</h3>
        <p>When, while the lovely valley teems with vapour around meand the</p>
    </div>
</template>
<script>
export default {
    name: 'StartVue'
}
</script>
<style scoped>
.services{
    display: flex;
    gap: 10px;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    padding-bottom: 80px;
}
.services p:first-child{
    color: #F9636B;
}
.services p:last-child{
    color: #3D3D3D;
}
h3{
    font-size: 30px;
    font-weight: 500;
    text-transform: capitalize;
}
span{
    font-weight: 700;
}

</style>