<template>
  <main class="bg-color q-px-xl row col-12  nav-position items-center justify-center">
    <div class="row  col-12 q-px-xl justify-between text-h6  ">
      <div class="col-5 items-center text-h2 text-secondary text-weight-bolder">
       K<span class="text-h5 text-primary">abita</span>
      </div>
      <div class="row  col-6 ">
        <div class="row col-12  justify-between items-center">
          <div class="hover" >About Me</div>
           <div  class="hover">Academic Qualifications</div>
          <div  class="hover">Experiences</div>
           <div  class="hover">Projects</div>
          <div  class="hover">Contact Me</div>
          
        </div>
      </div>
    </div>
  </main>
</template>

<script>
export default {
    name:'ContainerHeader'

}
</script>

<style>
.nav-position
{
  position:fixed;
  z-index: 1;
  width:100vw;     
   height:100px;  
   background-color: white;   
}

.bg-color
{
  background-color: #f2f2f2;
}

</style>