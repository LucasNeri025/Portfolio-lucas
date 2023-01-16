<template>
    <div>
      <Topo/>
      <SegundaPag/>
      <Final/>
    </div>
</template>
  
<script>
import Final from '~/components/Final.vue';
import SegundaPag from '~/components/SegundaPag.vue';
import Topo from '~/components/Topo.vue';
  
export default {
    name: "projetos",
    components: { Final, Topo, SegundaPag },
    transitions:{
        name: 'home',
        mode: 'out-in'
    }
    
}
</script>
  
  
<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins&display=swap');
*{
    padding: 0;
    margin: 0;
}
body{
    background: #242424;
}
.home-enter-active, .home-leave-active { transition: opacity 4s; }
.home-enter, .home-leave-active { opacity: 0; }
</style>