<template>
  <div>
    <Navbar />
    <pageHeader />
    <Overview />
    <nuxt/>
    <tableFilter />
    <Table />
  </div>
</template>

<script>
import pageHeader from '../components/pageHeader.vue'
import Navbar from '../components/Navbar.vue'
import Overview from '../components/Overview.vue'
import tableFilter from '../components/tableFilter.vue'
import Table from '../components/Table.vue'


export default {
  components: {
    pageHeader,
    Navbar,
    Overview,
    tableFilter,
    Table
}
}
</script>
