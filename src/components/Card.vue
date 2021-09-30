<template>
    <div class="card-element">
        <img :src="image" alt="">
        <p>{{title}}</p>
        <p>{{author}}</p>
        <p>{{year}}</p>
    </div>
</template>

<script>
export default {
    props: ["image", "title", "author", "year"],
    data: function(){
        return{
        
        }
    },

}

</script>

<style lang="scss" scoped>
@import "../style/variables.scss";

.card-element{
    margin:5px;
    text-align: center;

    background-color: white;

    flex-basis: calc(100% / 5 - 25px );
}

img{
    height: 60%;
    width: 60%;
}
</style>