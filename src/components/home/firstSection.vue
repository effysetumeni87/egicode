<template>
   <div class="window-height bg-grey-1 ">
    <q-card flat>
      <div class="row">
        <q-img    style="height:92vh;" src="statics/banner4.jpg"  >
           <div class="absolute-full transparent  flex  flex-center  ">
         <div class="row text-center">
           <div class=" q-pt-xl ">
             <div class="  text-weight-bold text-h3 text-blue-grey-10">
             <q-img style="max-width:300px;max-height:300px;"     src="statics/outline11.png" />
             </div>
               <!-- <my-divider /> -->
               <div class="row justify-center">
                  <div class="q-ma-lg text-weight-regular col-8  text-h6 text-blue-grey-10">
                    Our aim is to pilot approaches for greater engagement between Citizens, Civil Society Organizations (CSOs), Government, and Private Sector for improved economic governance. 
                  </div>
               </div>
              
              <div class=" text-weight-light text-h6">
              <q-btn label="learn more" outline rounded color="blue-grey-10" to="/about" />
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
// import myDivider from "../myDivider"
export default {
 components: {
    //  myDivider
 }
}
</script>

<style>

</style>