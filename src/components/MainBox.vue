<template>
    <main>
        <main-jumbotron/>
        <main-clients/>
        <main-finance/>
        <main-services/>
        <main-statistics/>
        <main-feedback/>
        <main-contact/>
    </main>
</template>

<script>
import MainJumbotron from './MainJumbotron.vue'
import MainClients from './MainClients.vue'
import MainFinance from './MainFinance.vue'
import MainServices from './MainServices.vue'
import MainStatistics from './MainStatistics.vue'
import MainFeedback from './MainFeedback.vue'
import MainContact from './MainContact.vue'

export default {
    components: {
        MainJumbotron,
        MainClients,
        MainFinance,
        MainServices,
        MainStatistics,
        MainFeedback,
        MainContact
    }
}
</script>

<style lang="scss" scoped>

</style>