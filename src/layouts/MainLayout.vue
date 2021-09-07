<template>
<main>
  <ContainerHeader/>
   <router-view class="view-padding"/>
  </main>
</template>

<script >
import ContainerHeader from 'src/components/partial/ContainerHeader.vue';



export default ({
  
   components: { ContainerHeader},

})
</script>
<style>
.view-padding
{
  padding-top:110px;
}
</style>, ContainerHeader