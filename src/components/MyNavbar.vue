<template>
    <div class="title">
        <h1>DASHBOARD</h1>
        <div>
            <img src="../assets/EscottLogo.png" alt="">
        </div>
    </div>
</template>

<script>
export default {
    name : 'MyNavbar'
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Lora:wght@700&display=swap');

.title{
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: space-between;
    background: #16B7DB;
}
img{
    margin-top: 12px;
    width: 25vh;
    margin-right: 1vh;
}
h1{
    color: white;
    margin-left: 3vh;
    margin-top: 2.5vh;
    font-family: 'Lora', serif; 
}
@media screen and (max-width: 1200px) {
    .title {
        width: auto;
        height: auto;
    }
}
</style>
