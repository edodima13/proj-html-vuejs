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
</style>