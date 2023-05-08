<template>
  <div>
    <navbar></navbar>
    <section>
      <a href="#">wasd</a>
      <h1>hello</h1>
    </section>
  </div>
</template>

<script>
import navbar from '@/components/nav.vue';
export default {
  name: 'App',
  components: {
    navbar
  }
}
</script>

<style lang="scss">
@import 'styles/reset.css'; // css reset
@import 'styles/variables.scss'; // Catppuccin color scheme
section {
  background: DarkSlateBlue;
  a {
    color: white;
  }
  h1 {
    color: $text;
  }
}
</style>
