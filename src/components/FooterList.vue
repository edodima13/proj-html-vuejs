<template>
    <div>
        {{info}}
    </div>
</template>
<script>

export default {
    name: 'FlistsVue',
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
        padding-bottom: 5px;
        font-size: 11px;
        color: #AAAAAA;
    }
</style>