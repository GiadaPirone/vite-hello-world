<script>
import AppHeader from './components/AppHeader.vue'
import AppText from './components/AppText.vue'
import AppFooter from './components/AppFooter.vue'

export default {
  components: {
    AppHeader,
    AppText,
    AppFooter
  }
}
</script>


<template>
  <header>
    <AppHeader />
  </header>

  <main>
    <AppText/>
  </main>

  <footer>
    <AppFooter/>
  </footer>

</template>

<style scoped></style>
