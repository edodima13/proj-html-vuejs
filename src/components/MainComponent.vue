<template>
    <main>
        <TryVue/>
        <ServiceVue/>
        <TryVue2/>
        <PortfolioVue/>
        <PricesVue/>
    </main>
</template>
<script>
import TryVue from './Try.vue'
import ServiceVue from './Services.vue'
import TryVue2 from './TryVue2.vue'
import PortfolioVue from './PortfolioComponent.vue'
import PricesVue from './PricesComponent.vue'


export default{
  components: { TryVue, ServiceVue, TryVue2, PortfolioVue, PricesVue },
    name: 'MainVue'
}
</script>
<style scoped>

</style>