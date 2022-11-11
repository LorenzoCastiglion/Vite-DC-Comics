<template>
  <HeaderComponent />
  <JumbotronComponent />
  <MainComponent />
  <FasciaBluComponent />
  <FooterComponent />
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue';
import FooterComponent from './components/FooterComponent.vue';
import MainComponent from './components/MainComponent.vue';
import FasciaBluComponent from './components/FasciaBluComponent.vue';
import JumbotronComponent from './components/JumbotronComponent.vue';

export default {

  data() {
    return
  },

  components: {
    HeaderComponent,
    FooterComponent,
    MainComponent,
    FasciaBluComponent,
    JumbotronComponent
  }


}

</script>

<style lang="scss">

</style>