<template>
  <q-layout view="lHh Lpr lFf">
    <q-header   class="bg-blue-grey-10">
      <div class="row justify-center content-center">

      
      <q-toolbar class="col-2 bg-black">
        <!-- <div>
        <q-btn size="sm" flat round class=" text-green" icon="ion-logo-facebook" text-color="green"   />
        <q-btn size="sm" flat round class="text-green" icon="ion-logo-twitter"     />
        <q-btn size="sm" flat  round class="text-green" icon="ion-logo-youtube"    />
      </div>  -->
      <q-separator  vertical inset />
      <q-img src="statics/egilogo.png" />
         <q-toolbar-title class="text-white text-weight-bold">
         The Urology Practice   
         </q-toolbar-title>

        <!-- <div>Quasar v{{ $q.version }}</div> -->
      </q-toolbar>
      <q-toolbar class="col-9 bg-blue-grey-9 justify-center">
           <q-btn flat label="home" to="/"/>
           <q-btn flat label="about us" to="/about" />
            <q-btn flat label="Services " to="/procedures" />

           <q-btn flat label="contact" to="/contact"/>
            
           
                     
      </q-toolbar>
      <q-toolbar class="col-1 black">
           <q-btn outline label="login" to="/"/>                       
      </q-toolbar>
      </div>
    </q-header>

    <q-drawer
      v-model="leftDrawerOpen"
     
      bordered
      content-class="bg-grey-2"
    >
      <q-list>
        <q-item-label header>Menu</q-item-label>
        <q-item clickable tag="a" to="/">
          <q-item-section avatar>           
          </q-item-section>
          <q-item-section>
            <q-item-label>Home</q-item-label>            
          </q-item-section>
        </q-item>

        <q-item clickable tag="a" to="/about" >         
          <q-item-section>
            <q-item-label>About Us</q-item-label>           
          </q-item-section>
        </q-item>

        <q-item clickable tag="a" to="/procedures">
          <!-- <q-item-section avatar>
                <q-icon name="chat" />
          </q-item-section> -->
          <q-item-section>
            <q-item-label>Services</q-item-label>
            
          </q-item-section>
        </q-item>
        <q-item clickable tag="a"  to="/contact">
         
          <q-item-section>
            <q-item-label>Contact</q-item-label>
            
          </q-item-section>
        </q-item>
        
      </q-list>
    </q-drawer>

    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script>
export default {
  name: 'MyLayout',

  data () {
    return {
      leftDrawerOpen: false
    }
  }
}
</script>
