<template>
    <div class="conteiner">
        <h2>PROJETOS</h2> 
        <div class="conteinerProjects">
            <div class="card">
                <img src="../assets/imgs/projeto-cadastro.webp" alt="foto da pagina projeto cadastro">
                <a href="https://cadastroapp.netlify.app/" target="_blank" rel="noopener noreferrer">
                    <p><b>PROJETO CADASTRO FUNCIONARIOS</b><br>Projeto criado desde a API em Node.js, onde usei Express, MongoDB, Bcript e JWT.
                    No Front-end utilizei Vue, Nuxt, HTML e CSS.
                </p>
                </a>
            </div>
            <div class="card">
                <img src="../assets/imgs/notes.webp" alt="foto da pagina notes">
                <a href="https://noteslucas.netlify.app/" target="_blank" rel="noopener noreferrer">
                    <p><b>BLOCO DE NOTAS</b><br>Projeto que fiz para uso cotidiano. Criado com Nuxt, Vue, CSS, HTML.
                </p>
                </a>
            </div>
            <div class="card">
                <img src="../assets/imgs/jogodavelha.webp" alt="foto da pagina jogo da velha">
                <a href="https://jogodavelhadoneri.netlify.app/" target="_blank" rel="noopener noreferrer">
                    <p><b>JOGO DA VELHA</b><br>Projeto que tinha muita vontade de fazer. Criado com JS, HTML e CSS.
                </p>
                </a>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name:'SegundaPag',   
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Poppins&display=swap');
.conteiner{
    width: 100vw;
    height: 80vh;
    background: #242424;
    overflow: auto;
}
h2{
    font-family: 'Poppins', sans-serif;
    color: #ffffff;
    font-size: 20px;
    text-align: center;
}
.conteinerProjects{
    width: 95vw;
    margin-top: 10px;
    margin: 0 auto;
    height: 100%;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
}
a{
    text-decoration: none;
}
.card{
    position: relative;
    width: 400px;
    height: 350px;
    display: flex;
    flex-direction: column;
    align-items: center;
    margin: 10px;
    box-sizing: border-box;
}
.card img{
    width: 400px;
    height: 250px;
    border-radius: 10px;
}
.card p{
    text-align: center;
    background:#D9D9D9;
    border-radius: 10px;
    font-family: 'Poppins', sans-serif;
    font-size: 15px;
    transition: .3s;   
    color: black; 
}
.card p:hover{
    transition: .3s;
    transform: scale(105%);
}
@media (max-width:768px) {
    .card{
        width: 300px;
        height: 250px;
        margin: 20px;
    }
    .card img{
        width: 300px;
        height: 250px;
    }
}
</style>