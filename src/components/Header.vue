<template>
    <div id="header-section">
        <div class="container-fluid">
            <div class="row">
                <div class="col-12 " id="my-container-logo">
                    <img src="../assets/imagess/spotify-logo.jpg" alt="">
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>

@import "../style/variables.scss";
@import "../style/general.scss";

#header-section{
    background-color: rgb(0, 22, 63);
    height: 10vh;
    
}

#my-container-logo{
    height: 10vh;
    img{
        height: 100%;
    }
}

</style>