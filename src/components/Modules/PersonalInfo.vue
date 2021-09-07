<template>
  <main>
      <div class="row col-12">
          <div class="col-6">
              <div class="row q-pa-xl justify-center">
               <q-img src="../../assets/kabita.jpg" height="400px" width="400px" />   
              </div>
          </div>
          <div class="col-6">
              <div class="column q-pa-xl q-gutter-y-lg">
                <div class="text-h4 text-secondary text-weight-bold">Personal Information</div>
                <div class="text-h6 text-secondary">
                    Name: <span class="text-black">Kabita Maharjan</span>
                </div>
                <div class="text-h6 text-secondary">
                    Address :<span class="text-black"> Nayabazar-16, Kathmandu</span>
                </div>
               <div class="text-h6 text-secondary">
                    Phone:<span class="text-black"> +977-9841266702</span>
                </div>
                <div class="text-h6 text-secondary">
                    Email:<span class="text-black"> Kabitamaharjan10@gmail.com</span>
                </div>
                 <div class="hover"><q-btn  rounded color="secondary" padding="12px" push label="RESUME" icon="download"/> </div>
                 <div class="row q-gutter-x-lg">
                 <q-icon name="facebook" size="30px" color="secondary" class="hover" @click="facebook"/>
                 <q-icon name="fab fa-linkedin" size="30px" color="secondary" class="hover" @click="linkedin"/>
                 <q-icon name="fab fa-instagram" size="30px" color="secondary" class="hover" @click="instagram"/>
                 </div>
              </div>

          </div>
      </div>
  </main>
</template>

<script>
export default {
    name:'PersonalInfo',
    methods:
    {
        facebook()
        {
            window.open('https://www.facebook.com/kabita.maharjan.526/')
        },
        linkedin()
        {
            window.open('https://www.linkedin.com/in/kabita-maharjan/')
        },
        instagram()
        {
            window.open('https://www.instagram.com/_kabitamaharjan_/')
        }
    }

}
</script>

<style>

</style>