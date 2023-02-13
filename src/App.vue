<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  data() {
    return {
      count: 0
    }
  },

  components: {
    AppHeader,
    AppMain,
    AppFooter
  }
}
</script>

<template>
  <button @click="count++">Count is: {{ count }}</button>
</template>

<style lang="scss">
@import './styles/main';

button {
  font-weight: bold;
}
</style>

