<script setup>

</script>

<template>
    <div class="container">
        <div class="content">
            <img src="/src/assets/logoSite.png" alt="">
            <p>Read more and stress less with our online book shopping app. Shop from anywhere you are and discover titles that you love. Happy reading!</p>
            <button class="start">Get Started</button>
            <button class="register">Register</button>
        </div>
    </div>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300..800;1,300..800&display=swap');

.content{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    margin-top: 184px;
}
img{
    width: 187px;
    height: 187px;
}
p{
    text-align: center;
    margin-top: 133px;
    font-size: 16px;
    font-family: "Open Sans", serif;

}
button{
    width: 320px;
    height: 56px;
    border-radius: 5px;
}
.start{
    margin-top: 77px;
    border: none;
    outline: none;
    background-color: black;
    color: white;
    font-size: 14px;
    cursor: pointer;
}
.start:hover{
    background-color: rgb(28, 26, 26);
    transition: 200ms;
}
.register{
    margin-top: 40px;
    background-color: transparent;
    border: none;
    outline: none;
    font-size: 16px;
    border: 1px solid;
    cursor: pointer;
}
.register:hover{
    background-color: rgb(240, 237, 237);
    transition: 200ms;
}
</style>