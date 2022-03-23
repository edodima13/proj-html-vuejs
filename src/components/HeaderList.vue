<template>
    <div class="container-info">
        {{info}}
    </div>
</template>
<script>

export default {
    name: 'HlistVue',
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
    .container-info{
        color: white;
        font-size: 14px;
    }
</style>
