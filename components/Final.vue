<template>
    <div class="conteiner">
        <div class="conteinerSvgs">
            <nuxt-link to="/" class="linknuxt"><p class="link">HOME</p></nuxt-link>
            <nuxt-link to="/projetos" class="linknuxt"><p class="link">PROJETOS</p></nuxt-link>
            <nuxt-link to="/habilidades" class="linknuxt"><p class="link">HABILIDADES</p></nuxt-link>
            <nuxt-link to="/contato" class="linknuxt"><p class="link">CONTATO</p></nuxt-link>
        </div>
    </div>
</template>

<script>
export default {
    name:'Final',
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Poppins&display=swap');
.conteiner{
    position: fixed;
    bottom: 0;
    width: 100vw;
    height: 8vh;
    background: #D9D9D9;
    display: flex;
    justify-content: center;
    align-items: center;
    box-sizing: border-box;
    border-radius: 20px 20px 0px 0;
}
.conteinerSvgs{
    width: 90vw;
    height: 90%;
    display: flex;
    align-items: center;
    justify-content: space-around;
}
.link{
    text-decoration: none;
    font-family: 'Poppins', sans-serif;
    cursor: pointer;
    transition: .3s;
    color: black;
    text-decoration-style: none;
    font-size: 18px;
}
.link:hover{
    transition: .3s;
    transform: scale(120%);
}
.linknuxt{
    text-decoration: none;
}
@media (max-width:786px) {
    .link{
        font-size: 14px;
    }
}
</style>