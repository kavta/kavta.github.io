<template>
  <main>
   <Aboutme/>
   <!-- <PersonalInfo/> -->
   <Education/>
   <!-- <Experiences/> -->
   <Skills/>
   <Project/>
   
    </main>
</template>

<script lang="ts">

import Aboutme from 'src/components/Modules/Aboutme.vue';
import Education from 'src/components/Modules/Education.vue';
import Experiences from 'src/components/Modules/Experiences.vue';
import Skills from 'src/components/Modules/Skills.vue';

import Project from 'src/components/Modules/Project.vue';


export default({
  components: { Aboutme, Education ,Skills, Project },
  name: 'PageIndex',
});
</script>
