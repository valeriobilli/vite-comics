<script>
import AppHeader from './components/AppHeader.vue'
import AppContent from './components/AppContent.vue'
import AppMainNavbar from './components/AppMainNavbar.vue'
import AppLinks from './components/AppLinks.vue'
import AppFooter from './components/AppFooter.vue'


export default {
  components: {
    AppHeader,
    AppContent,
    AppMainNavbar,
    AppLinks,
    AppFooter,
  }
}
</script>

<template>
  <AppHeader />
  <AppContent />
  <AppMainNavbar />
  <AppLinks />
  <AppFooter />
</template>

<style scoped lang="scss"></style>
