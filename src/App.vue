<script>
import AppHeader from './components/AppHeader.vue';

export default {
  name:'App',
  component:{
    AppHeader,
  } 
}

</script>


<template>
<AppHeader />

</template>


<style lang="scss">
@use './styles/partials/variables' as *;
@use './styles/general.scss' as *;

</style>
