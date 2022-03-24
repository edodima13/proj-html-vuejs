<template>
    <div>
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
        padding-left: 100px;
        text-align: center;
    }
</style>