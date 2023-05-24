<script>
import AppHeader from './components/AppHeader.vue'
import AppContent from './components/AppContent.vue'
import AppMainNavbar from './components/AppMainNavbar.vue'


export default {
  components: {
    AppHeader,
    AppContent,
    AppMainNavbar
  }
}
</script>

<template>
  <AppHeader />
  <AppContent />
  <AppMainNavbar />
</template>

<style scoped></style>
