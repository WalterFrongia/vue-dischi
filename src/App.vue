<template>
  <div id="app">
    <Header/>
    <Content/>
  </div>
</template>

<script>
// import axios from 'axios' (fino a quando non lo utilizzo non devo importarlo)
import Header from './components/Header.vue'
import Content from './components/Content.vue'

export default {
  components: {
    Header,
    Content,
  }
}
</script>

<style lang="scss">
@import '~bootstrap/scss/bootstrap';
@import "./style/variables.scss";
@import "./style/general.scss";

</style>
