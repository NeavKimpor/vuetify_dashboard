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
    height: 20%;
    display: flex;
    justify-content: space-between;
    background: #16B7DB;
}
img{
    margin-top: 15px;
    width: 180px;
    margin-right: 10px;
}
h1{
    color: white;
    margin-left: 20px;
    margin-top: 18px;
    font-family: 'Lora', serif; 
}
</style>
