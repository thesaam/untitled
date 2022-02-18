<template>
  <div>
    <Navbar />
    <pageHeader />
    <Overview />
    <nuxt/>
  </div>
</template>

<script>
import pageHeader from '../components/pageHeader.vue'
import Navbar from '../components/Navbar.vue'
import Overview from '../components/Overview.vue'


export default {
  components: {
    pageHeader,
    Navbar,
    Overview
}
}
</script>
