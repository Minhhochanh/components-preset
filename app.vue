<template>
<body>
  <div id="app">
    <headercomp />
    <bodycomp />
    <termcomp />
    <offercomp/>
    <footercomp/>
  </div>
  </body>
</template>

<script>
import headercomp from './src/components/header-comp.vue';
import bodycomp from './src/components/body.vue';
import termcomp from './src/components/TermsSection.vue';
import offercomp from './src/components/offer.vue';
import footercomp from './src/components/footer-comp.vue';

export default {
  name: 'App',
  components: {
    headercomp,
    bodycomp,
    termcomp,
    offercomp,
    footercomp,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
