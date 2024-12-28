<script setup>

</script>

<template>
<div class="container">
    <div class="topPage">
        <img src="/src/assets/back.png" alt="">
    <div class="tittle">
        <h1>Get Started</h1>
    </div>
    </div>
    <div class="content">
    <div class="login">
            <p>Please fill your details to login.</p>
            <input type="text" placeholder="Username/Email">
            <input type="password" placeholder="Senha">
            <button class="submit">LOGIN</button>
    </div>
    <a href="">Forgot Password?</a>
    <a class="register" href="">New member? Register</a>
    </div>
</div>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300..800;1,300..800&display=swap');


.topPage{
    display: flex;
    align-items: center;
    margin-top: 60px;
}
img{
    width: 24px;
    height: 24px;
    margin-left: 16px;
    cursor: pointer;
}
.tittle{
    width: 100%;
    display: flex;
    justify-content: center;
}
h1{
    font-size: 24px;
    font-weight: bold;
    font-family: "Open Sans", serif;
}
.content{
    margin-top: 72px;
    display: flex;
    flex-direction: column;
}
p{
    text-align: justify;
    font-size: 16px;
    font-family: "Open Sans", serif;
    margin-bottom: 32px;
}
.login{
    margin: auto;
}
input{
    display: flex;
    width: 320px;
    height: 56px;
    border-radius: 5px;
    border: 2px solid black;
    margin-top: 24px;
    padding-left: 11px;
    font-size: 15px;
}
.submit{
    width: 334px;
    background-color: black;
    color: white;
    cursor: pointer;
    margin-top: 24px;
    font-size: 15px;
    border-radius: 5px;
    height: 56px;
}
.submit:hover{
    background-color: transparent;
    color: black;
    transition: 250ms;
}
a{
    text-align: center;
    font-size: 17px;
    margin-top: 24px;
    color: black;
    font-family: "Open Sans", serif;
}
.register{
    margin-top: 235px;
}
</style>