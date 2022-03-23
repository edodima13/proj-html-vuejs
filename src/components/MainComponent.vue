<template>
    <main>
        <TryVue/>
        <ServiceVue/>
    </main>
</template>
<script>
import TryVue from './Try.vue'
import ServiceVue from './Services.vue'

export default{
  components: { TryVue, ServiceVue },
    name: 'MainVue'
}
</script>
<style scoped>

</style>