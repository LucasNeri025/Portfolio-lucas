<template>
    <div class="conteiner">
        <div class="title"><h2>Lucas Neri</h2></div>
    </div>
</template>

<script>
export default {
    name:'Topo'
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Poppins&display=swap');
.conteiner{
    width: 100vw;
    height: 10vh;
    background: #242424;
    display: flex;
    justify-content: center;
    align-items: center;
    box-sizing: border-box;
}
.title h2 {
    font-family: 'Poppins', sans-serif;
    color: #ffffff;
    font-size: 22px;
    transition: .3s;
}
.title h2:hover{
    transition: .3s;
    transform: scale(120%);
}
</style>