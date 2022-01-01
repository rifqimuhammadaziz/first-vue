<template>
    <div class="logos-wrapper">
        <h2 class="title-header">Find Best Logo</h2>
        <div class="item-logos">
            <img class="logo" src="../assets/google.png" alt="Google Logo">
        </div>
        <div class="item-logos">
            <img class="logo" src="../assets/microsoft.png" alt="Microsoft Logo">
        </div>
        <div class="item-logos">
            <img class="logo" src="../assets/starbuck.png" alt="Starbuck Logo">
        </div>
        <div class="item-logos">
            <img class="logo" src="../assets/apple.png" alt="Apple Logo">
        </div>
        <div class="item-logos">
            <img class="logo" src="../assets/oracle.png" alt="Oracle Logo">
        </div>
        <div class="item-logos">
            <img class="logo" src="../assets/golang.png" alt="Golang Logo">
        </div>
        <div class="item-logos">
            <img class="logo" src="../assets/google.png" alt="Google Logo">
        </div>
        <div class="item-logos">
            <img class="logo" src="../assets/microsoft.png" alt="Microsoft Logo">
        </div>
        <div class="item-logos">
            <img class="logo" src="../assets/starbuck.png" alt="Starbuck Logo">
        </div>
        <div class="item-logos">
            <img class="logo" src="../assets/apple.png" alt="Apple Logo">
        </div>
        <div class="item-logos">
            <img class="logo" src="../assets/oracle.png" alt="Oracle Logo">
        </div>
        <div class="item-logos">
            <img class="logo" src="../assets/golang.png" alt="Golang Logo">
        </div>
    </div>
</template>

<script>
export default {
    name: 'Logos',
}
</script>

<style scoped>
.title-header {
    text-align: left;
    margin-bottom: 80px;
}
.logos-wrapper {
    width: 70%;
    overflow: hidden;
    margin: auto;
}

.item-logos {
    float: left;
    margin-right: 70px;
    margin-bottom: 70px;
    width: 150px;
    height: 150px;
}

.item-logos .logo {
    width: 150px;
    height: 150px;
}
</style>