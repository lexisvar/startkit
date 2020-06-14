<template>
  <div>
    <navbar />
    <app-main />
    <footer-b />
  </div>
</template>

<script>
import { Navbar, FooterB, AppMain } from './components/front';

export default {
  name: 'Layout',
  components: {
    Navbar, FooterB, AppMain,
  },
  mixins: [],
  computed: {

  },
  methods: {

  },
};
</script>

<style lang="scss" scoped>

</style>
