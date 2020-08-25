<template>
  <div> 
        
            <!-- <div :speed="0.8" :height="400"
      src="statics/banner.jpg" -->
      <div
      style="background-color:#fcfcfc;"

    >
    <q-card class="shadow-4" style="background-color:#00000014;">
          <q-card-section class="text-center text-green text-h5 text-weight-bold">
              OUR SERVICES
              <my-divider />
          </q-card-section>
          <q-card-section>
               <div class="row text-center justify-center">
                 <div class="col-12">
                     <div class="row justify-center">
                       <q-card  v-for="service in services" :key="service.title" class="q-ma-xs col-3  text-weight-bolder" >
                        <q-card-section>
                        <q-img style="height: 200px; width:250px" :src="service.image" />
                        </q-card-section>
                           <q-card-actions class="bg-green text-white row justify-center ">
                             <div class="text-center row justify-center bg-green">
                                {{service.title}}
                             </div>
                             
                           </q-card-actions>
                       </q-card>
                        
                     </div>
                     <div>
                     <q-btn outline label="learn more" color="green" to="/procedures" />
                      
                     </div>
                 </div>
               </div>
          </q-card-section>
    </q-card>
            </div>
         
      </div>
</template>

<script>
import myDivider from "../myDivider"
export default {
components: {
    myDivider
},
data(){
  return {
      services : [
        {title: "General Urology",
             image: "statics/general.jpg",
             description: ""},
              {title: `Paediatric Urology `,
             image: "statics/paed.jpg",
             description: ""},
              {title: "Reconstructive Urology ",
              image: "statics/recon.jpg",
             description: ""},
             ]
  }
}

}
</script>

<style>

</style>