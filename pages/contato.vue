<template>
    <div>
      <Topo/>
      <redes-sociais/>
      <Final/>
    </div>
</template>
  
<script>
import Final from '~/components/Final.vue';

import Topo from '~/components/Topo.vue';
  
export default {
    name: "contato",
    components: { Final, Topo},
    
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