<script setup></script>

<template>
    <nav>
        <h1 class="happyMessage">Happy Reading!</h1>
        <img class="search" src="/src/assets/search.png" alt="">
    </nav>
    <div class="content">
        
    </div>
</template>

<style scoped>
nav{
    display: flex;
    justify-content:space-between;
    margin: 18px;
}
.happyMessage{
    font-size: 16px;
    font-family: "Open Sans", serif;
}
.search{
    height: 32px;
    width: 32px;
    cursor: pointer;
}
</style>