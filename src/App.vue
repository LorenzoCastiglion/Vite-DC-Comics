<template>
  <HeaderComponent />
  <MainComponent />
  <FasciaBluComponent />
  <FooterComponent />
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue';
import FooterComponent from './components/FooterComponent.vue';
import MainComponent from './components/MainComponent.vue';
import FasciaBluComponent from './components/FasciaBluComponent.vue';

export default {

  data() {
    return
  },

  components: {
    HeaderComponent,
    FooterComponent,
    MainComponent,
    FasciaBluComponent
  }


}

</script>

<style lang="scss">

</style>