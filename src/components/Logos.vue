<template>
    <div class="logos-wrapper">
        <h2 class="title-header">Find Best Logo</h2>
        <div class="item-logos">
            <img class="logo" src="../assets/01.png" alt="">
        </div>
        <div class="item-logos">
            <img class="logo" src="../assets/02.png" alt="">
        </div>
        <div class="item-logos">
            <img class="logo" src="../assets/03.png" alt="">
        </div>
        <div class="item-logos">
            <img class="logo" src="../assets/04.png" alt="">
        </div>
        <div class="item-logos">
            <img class="logo" src="../assets/05.png" alt="">
        </div>
        <div class="item-logos">
            <img class="logo" src="../assets/06.png" alt="">
        </div>
        <div class="item-logos">
            <img class="logo" src="../assets/07.png" alt="">
        </div>
        <div class="item-logos">
            <img class="logo" src="../assets/08.png" alt="">
        </div>
        <div class="item-logos">
            <img class="logo" src="../assets/09.png" alt="">
        </div>
        <div class="item-logos">
            <img class="logo" src="../assets/10.png" alt="">
        </div>
    </div>
</template>

<script>
export default {
    name: 'LogosView',
}
</script>

<style scoped>
.title-header {
    margin-bottom: 80px;
    text-align: left;
}

.logos-wrapper {
    width: 70%;
    overflow: hidden;
    margin: auto;
}

.item-logos {
    float: left;
    margin-right: 10px;
    margin-bottom: 10px;
    width: 150px;
    height: 150px;
}

.item-logos .logo {
    width: 150px;
    height: 150px;
}
</style>