<template>
  <AppTitle />
  <AppHero />
</template>

<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';


export default {
  name: 'App',
  components: {
      AppTitle,
      AppHero
  }
}
</script>

<style lang="scss" scoped></style>