<template>
    <main>
        <TryVue/>
        <ServiceVue/>
        <TryVue2/>
    </main>
</template>
<script>
import TryVue from './Try.vue'
import ServiceVue from './Services.vue'
import TryVue2 from './TryVue2.vue'

export default{
  components: { TryVue, ServiceVue, TryVue2 },
    name: 'MainVue'
}
</script>
<style scoped>

</style>