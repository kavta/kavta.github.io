<template>
  <main class="q-pa-xl">
      <div class="row col-12">
          <div class="column items-center col-6 q-gutter-y-lg">
            <div class=" items-center ">
                <q-icon name="school" color="secondary" size="80px" class="q-px-lg" />
                <div class=" text-h4 text-secondary">My Academic Qualifications</div>
            </div>
            <div>
                <q-card dark bordered class=" my-card">
                    <q-card-section>
                        <div class="text-h6">Bachelor in Information Management, BIM<br/> 1st Division (2016 - 2021)</div>
                        <div class="text-subtitle2">National College of Computer Studies (NCCS), Paknajol</div>
                    </q-card-section>
                    <q-card-section>
                        <div class="text-h6">+2, <br/>1st Division (2014 - 2016)</div>
                        <div class="text-subtitle2">NCCS Higher Secondary School, Paknajol</div>
                    </q-card-section>
                    <q-card-section>
                        <div class="text-h6">SLC, <br/>1st Division (2009 - 2014)</div>
                        <div class="text-subtitle2">Siddhartha Vanasthali Institute, Banasthali</div>
                    </q-card-section>
                </q-card>
            </div>
        </div>
        <div class="col-6 q-gutter-y-lg">
           <div class="column justify-center items-center ">
                <q-icon name="work" color="secondary" size="80px" class="q-px-lg" />
                <div class="text-h4 text-secondary ">Skills</div>
            </div>
            <div class="row justify-center q-gutter-x-xl">
                <q-card dark bordered class="skill-my-card ">
                        <q-card-section>
                            <div class="text-h6">Soft Skills</div>
                            <div class="text-subtitle2">Communication <br/> Leadership</div>
                        </q-card-section>
                </q-card>
                  <q-card dark bordered class="skill-my-card ">
                    <q-card-section>
                        <div class="text-h6">Software Development Skills</div>
                        <div class="text-subtitle2">HTML</div>
                    </q-card-section>
                </q-card>
            </div>
        </div>
      </div>
      <!-- </div> -->
  </main>
</template>

<script>
export default {
    name:'Education'

}
</script>

<style lang="scss" scoped>
.my-card{
  height: auto;
  width: 550px;
  background-color: #5d82aa;
}
.skill-my-card{
    height:auto;
    width: 300px;
      background-color: #5d82aa;
}


</style>