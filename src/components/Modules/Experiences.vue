<template>
  <main class="q-pa-xl">
     <div class="row col-12">
      <div class=" col-3 text-h2 items-center justify-center ">
          <q-icon name="verified" color="secondary" size="80px" class="q-px-lg" />
          <div class="text-secondary  text-h4"> Experiences</div>
        </div>
        <q-timeline layout="loose" class="q-pt-xl ">
      <q-timeline-entry v-for="(timeline,index) in timelineData"
      :key="index"
        :side="index%2==0?'left':'right'"
        :color="index%2==0?'secondary':'primary'"
        >
        <template v-slot:title v-if="index%2==0">
          <div class="text-h4 text-secondary text-weight-bold"> {{timeline.date}} </div>
        </template>
        <template v-slot:title v-else>
          <div class="text-h4 text-primary text-weight-bold"> {{timeline.date}} </div>
        </template>
        <template v-slot:subtitle >
           <div> <q-img  :src="require('../../assets/'+timeline.image)" height="150px" width="220px" /></div>
        </template>
        <div class="q-gutter-y-md">
        <div class="text-weight-bold text-h5">{{timeline.title}}</div>
            <div class="text-body1">
            {{timeline.description}}
          </div>
        </div>
      </q-timeline-entry>
       </q-timeline>
      </div>
      
  </main>
</template>

<script>
export default {
    name:'Experiences',
    data()
    {
        return{
           timelineData:[{
             date:'2020/11/30 – 2021/02/28',
               title:'Mobile Application Developer (Intern)',
               description:'Gurzu Inc (Jyaasa Technologies Pvt Ltd)',
               image:'gurzu-logo.png',
                
           },
            {
             date:'2021/06/01-Running',
               title:'Front-End Developer (Intern)',
               description:'Ktmbees',
              image:'ktmbees.png',
           }
           ]
            
        }

}
}
</script>

<style>
.q-timeline__subtitle{
  opacity: 1 !important;
}
</style>