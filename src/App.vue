<script>
import AppHeader from './components/AppHeader.vue';
import AppJumbotron from './components/AppJumbotron.vue';
import AppContent from './components/AppContent.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  name:'App',
  components:{
    AppHeader,
    AppJumbotron,
    AppContent,
    AppFooter,
  } 
}

</script>


<template>

<AppHeader/>

<main>
  <AppJumbotron />
  <AppContent />
</main>

<AppFooter/>

</template>


<style lang="scss">
@use './styles/partials/variables' as *;
@use './styles/general.scss' as *;

</style>
