<template>
  <div>
    <Topo/>
    <PrimeiraPag/>
    <Final/>
  </div>
</template>

<script>
import Final from '~/components/Final.vue';
import PrimeiraPag from '~/components/PrimeiraPag.vue';
import Topo from '~/components/Topo.vue';

export default {
    name: "IndexPage",
    components: { Final, Topo, PrimeiraPag }
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