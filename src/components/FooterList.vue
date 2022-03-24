<template>
    <div class="container-l">
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
    .container-info{
        color: white;
        font-size: 11px;
    }
</style>