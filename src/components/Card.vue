<template>
    <div class="card-element">
        <h1></h1>   
    </div>
</template>

<script>
export default {
    data: function(){
        return{
        
        }
    },

}

</script>

<style lang="scss" scoped>
@import "../style/variables.scss";

.card-element{
    height: 150px;
    margin:5px;

    background-color: white;

    flex-basis: calc(100% / 6 - 30px );
}
</style>