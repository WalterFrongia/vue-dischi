<template>
    <div class="card-element">
        <img :src="image" alt="">  
    </div>
</template>

<script>
export default {
    props: ["image"],
    data: function(){
        return{
        
        }
    },

}

</script>

<style lang="scss" scoped>
@import "../style/variables.scss";

.card-element{
    height: 200px;
    width: 200px;
    margin:5px;

    background-color: white;

    flex-basis: calc(100% / 6 - 30px );
}

img{
    height: 100%;
    width:100%;
}
</style>