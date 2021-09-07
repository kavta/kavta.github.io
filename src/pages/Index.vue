<template>
  <main>
   <Aboutme/>
   <!-- <PersonalInfo/> -->
   <Education/>
   <Experiences/>
   <Project/>
   
    </main>
</template>

<script lang="ts">

import Aboutme from 'src/components/Modules/Aboutme.vue';
import Education from 'src/components/Modules/Education.vue';
import Experiences from 'src/components/Modules/Experiences.vue';
import PersonalInfo from 'src/components/Modules/PersonalInfo.vue';
import Project from 'src/components/Modules/Project.vue';
import { defineComponent } from 'vue';

export default defineComponent({
  components: { Aboutme, Education, Experiences, Project },
  name: 'PageIndex',
});
</script>
