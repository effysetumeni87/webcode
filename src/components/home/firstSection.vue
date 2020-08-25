<template>
   <div class="window-height bg-grey-1 ">
    <q-card flat>
      <div class="row">
        <q-img    style="height:92vh;" src="statics/banner14.jpg"  >
           <div class="absolute-full transparent  flex  flex-center  ">
         <div class="row text-center">
           <div class=" q-pt-xl ">
             <div class="  text-weight-bold text-h3 text-blue-grey-10">
             The Urology Practice
             </div>
               <my-divider />
              <div class="q-ma-lg text-weight-regular text-h6 text-blue-grey-10">
              Providing  Quality Health Care Services 
             </div>
              <div class=" text-weight-light text-h6">
              <q-btn label="learn more" color="green" to="/about" />
             </div>
           </div>
         </div>    
           </div>
        </q-img>
      </div>
    </q-card>
  </div>
</template>

<script>
import myDivider from "../myDivider"
export default {
 components: {
     myDivider
 }
}
</script>

<style>

</style>