<template>
  <div id="app">
    <Header />

    <main>
      <Contents />
    </main>

    <Footer />

  </div>
</template>

<script>
  import Header from './components/Header.vue';
  import Contents from './components/Contents.vue';
  import Footer from './components/Footer.vue';

export default {
  name: 'App',
  components: {
    Header,
    Contents,
    Footer,
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
}
</style>
