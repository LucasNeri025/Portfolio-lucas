<template>
    <div class="conteiner">
            <div class="texto">
                <p>
                    <B>Eu sou um Desenvolvedor em fase de transição <br> </B>Tenho 21 anos, Iniciei 
                    o estudo na área de Programação há cerca de 06 meses, cursando análise 
                    e Desenvolvimento de software, na Estácio. Estou a procura de desafios 
                    para ampliar meu conhecimento.
                </p>
            </div>
            <div class="astronauta">
                <img src="../assets/imgs/astronaut.webp" alt="">
            </div>
    </div>
</template>

<script>
export default {
    name:'PrimeiraPag'
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Poppins&display=swap');
.conteiner{
    width: 100vw;
    height: 80vh;
    background: #242424;
    box-sizing: border-box;
    display: flex;
    justify-content: space-around;
    align-items: center;
}
.texto{
    width: 45vw;
}
.texto p {
    text-align: center;
    font-family: 'Poppins', sans-serif;
    color: #D9D9D9;
    font-size: 18px;
}
.texto p b {
    color: white;
    font-size: 20px;
    font-weight: 600;
}
.astronauta{
    width: 40vw;
    display: flex;
    align-items: center;
    justify-content: center;
}
.astronauta img {
    width:30vw;
    max-width: 40vw;
    animation: MoveUpDown 3s infinite;
    max-height: 80vh ;
}
@keyframes MoveUpDown {
  0%, 100% {
    transform: translateY(0);
  }
  50% {
    transform: translateY(-30px);
  }
}
@media (max-width: 768px){
    .conteiner{
        flex-direction: column;
    }
    .texto{
        width: 80vw;
    }
    .astronauta{
        width: 80vw;
    }
    .astronauta img{
       width: 60vw;
    }
}
</style>