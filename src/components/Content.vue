<template>
    <div id="content-section">
        <div id="cards-container">
            <card v-for="(card, index) in arrayMusic" :key="index" :image="card.poster" />      
        </div>
    </div>
</template>

<script>
import axios from 'axios'
import Card from './Card.vue'

export default {
    components: {
        Card
    },
    data: function(){
        return{
            arrayMusic: [],
        }
    },
    mounted() {
        axios.get('https://flynn.boolean.careers/exercises/api/array/music')
        .then((response) => {
        this.arrayMusic = (response.data.response);
        console.log(this.arrayMusic);
        });
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