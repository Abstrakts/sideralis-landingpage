<template>
  <v-app dark>
    <navbar />
    <firstSlide />
    <secondSlide />
    <thirdSlide />
    <forthSlide />
  </v-app>
</template>

<script>
import navbar from '../components/navbar.vue';
import firstSlide from '../components/firstSlide.vue';
import secondSlide from '../components/secondSlide.vue';
import thirdSlide from '../components/thirdSlide.vue';
import forthSlide from '../components/forthSlide.vue';





export default {
  data() {
    return {};
  },
  components: {
    navbar,
    firstSlide,
    secondSlide,
    thirdSlide,
    forthSlide
  }
};
</script>
