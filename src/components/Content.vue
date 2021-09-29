<template>
  <div id="content-section">
      <div id="cards-container">
          <Card/>
          <Card/>
          <Card/>
          <Card/>
          <Card/>
          <Card/>
      </div>
  </div>
</template>

<script>
import Card from './Card.vue'

export default {
    components: {
        Card
    }
}
</script>

<style lang="scss" scoped>
@import "../style/variables.scss";
@import "../style/general.scss"; 

#content-section{
    height:90vh;
    background-color:rgb(38, 38, 51);
}

#cards-container{
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
}
</style>