<template>
  <div id="app">
    <Header/>
    <Main/>
  </div>
</template>

<script>
// import axios from 'axios' (fino a quando non lo utilizzo non devo importarlo)
import Header from './components/Header.vue'
import Main from './components/Main.vue'

export default {
  components: {
    Header,
    Main,
  }
}
</script>

<style lang="scss">
@import '~bootstrap/scss/bootstrap';
@import "./style/variables.scss";
@import "./style/general.scss";

</style>
