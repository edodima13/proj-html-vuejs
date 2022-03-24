<template>
    <div class="links">
        {{info}}
    </div>
</template>
<script>

export default {
    name: 'FlistVue2',
    props: {
        info:{
            type: Array,
            required: true
        }
    },
    components:{
    }
}
</script>
<style scoped>
    div > div{
        padding-left: 50px;
        text-align: center;
        padding-bottom: 5px;
        font-size: 11px;
        color: #AAAAAA;
    }
</style>