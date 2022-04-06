<template>
  <section>
    <app-header />
    <getStarted />
    <benefits-list />
    <illustration />
    <review-list />
    <signUp />
    <app-footer />
  
  </section>
</template>

<script>
import appHeader from "./components/app-header.vue";
import getStarted from "./components/getStarted.vue";
import benefitsList from "./components/benefits-list.vue";
import illustration from "./components/illustration.vue";
import reviewList from "./components/review-list.vue"
import signUp from "./components/signUp.vue";
import AppFooter from './components/app-footer.vue';

export default {
  name: "app",
  components: {
    appHeader,
    getStarted,
    benefitsList,
    illustration,
    reviewList,
    signUp,
    AppFooter
},
};
</script>

