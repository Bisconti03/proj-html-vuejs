<script>
import InfoHeader from './components/InfoHeader.vue'
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  data() {
    return {
      
    }
  },

  components: {
    AppHeader,
    AppMain,
    AppFooter,
    InfoHeader,
  }
}
</script>

<template>

  <InfoHeader/>
  
 <AppHeader/>

 <AppMain/>

 <AppFooter/>
  
  
</template>

<style lang="scss">
@import './styles/main';


</style>

