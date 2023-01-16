<template>
    <div>
      <Topo/>
      <ferramentas/>
      <Final/>
    </div>
</template>
  
<script>
import Ferramentas from '~/components/ferramentas.vue';
import Final from '~/components/Final.vue';

import Topo from '~/components/Topo.vue';
  
export default {
    name: "habilidades",
    components: { Final, Topo, Ferramentas},
    
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
</style>