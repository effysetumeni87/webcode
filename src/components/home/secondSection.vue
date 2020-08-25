<template>
   <div class="row  ">  
      <div class="col-12 ">
         
      <div class="row justify-center bg-grey-1" >
        <q-card flat style="margin-top:-98px; border-radius:30px 30px 0px 0px;" class="col-xs-12 col-sm-8 col-md-8 col-lg-8 col-xl-8 bg-grey-1 text-white text-center">
           <div class="row  ">
             <q-toolbar class="col-6 bg-white text-right" style="  border-radius:30px 0px 0px 0px">
                   <q-toolbar-title class="text-weight-bold text-green" style="font-size: 16px">
                     CORE
                   </q-toolbar-title>
                     
             </q-toolbar>
             <q-toolbar class="col-6 bg-green text-left text-bold"  style="  border-radius:0px 30px 0px 0px">                
                   <q-toolbar-title class="text-weight-bold " style="font-size: 16px">
                     VALUES
                   </q-toolbar-title>                
             </q-toolbar>
           </div>
               <my-divider />
             <q-card-section>
              <div class="row justify-center">
                <div class="col-3 q-ma-sm">
                  <q-card dark class="bg-blue-grey-1 text-black text-weight-bolder text-blue-grey-10" flat bordered>
                  <q-card-section>
                    <q-img src="statics/icon3.png" />
                  </q-card-section>
                  <q-card-actions  style="color:#4caf50;" class="bg-white justify-center content-center text-center text-weight-bolder">  
                      <div>                  
                    PROFESSIONALISM 
                      </div>
                  </q-card-actions>
                  </q-card>
                </div>
                <div class="col-3 q-ma-sm">
                  <q-card dark class="bg-blue-grey-1 text-black text-weight-bold" flat bordered>
                  <q-card-section>
                    <q-img src="statics/icon2.png" />
                  </q-card-section>
                  <q-card-actions style="color:#4caf50;" class="bg-white   justify-center content-center text-center text-weight-bolder">
                  INTEGRITY
                  </q-card-actions>
                  </q-card>
                </div>
                <div class="col-3 q-ma-sm">
                  <q-card dark class="bg-blue-grey-1 text-black text-weight-bold" flat bordered >
                  <q-card-section>
                    <q-img src="statics/icon1.png" />
                  </q-card-section>
                  <q-card-actions  style="color:#4caf50;" class="bg-white justify-center content-center text-center text-weight-bolder">
                   QUALITY CARE
                  </q-card-actions>
                  </q-card>
                </div>
                
              </div>
             </q-card-section>
               
            </q-card>
      </div>
      
      </div>
         
    </div>
</template>

<script>
import myDivider from "../myDivider"
export default {
 components:{
     myDivider
 }
}
</script>

<style>

</style>