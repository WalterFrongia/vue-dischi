<template>
  <div id="app">
    <Header/>
    <Content/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Content from './components/Content.vue'

export default {
  components: {
    Header,
    Content,
  },
  data: function(){
        return{
        }
    },
}
</script>

<style lang="scss">
@import '~bootstrap/scss/bootstrap';
@import "./style/variables.scss";
@import "./style/general.scss";

</style>
