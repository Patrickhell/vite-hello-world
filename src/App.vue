<script>
import AppTitle from './components/AppTitle.vue';


export default (await import('vue')) .defineComponent({
  name : 'mainApp',
  components:{
    AppTitle
    
  }
})
</script>

<template>
  <AppTitle />

</template>

<style scoped>

</style>
