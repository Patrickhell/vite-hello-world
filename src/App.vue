<script>
import AppHero from './components/AppHero.vue';
import AppTitle from './components/AppTitle.vue';

export default (await import('vue')) .defineComponent({
  name : 'mainApp',
  components:{
    AppHero,
    AppTitle,
  }
})
</script>

<template>
  <AppHero />
  <AppTitle />

</template>

<style scoped>

</style>
