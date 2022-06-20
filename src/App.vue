<template>
  <div id="app">
    <TitlePage/>
    <HeroPage/>
  </div>
</template>

<script>
import TitlePage from '@/components/TitlePage.vue';
import HeroPage from '@/components/HeroPage.vue';

export default {
  name: 'App',
  components: {
    TitlePage,
    HeroPage
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  // margin-top: 60px;
}
</style>
