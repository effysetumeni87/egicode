<template>
  <div class="row">
      <div class="col-12 kustify-center bg-blue-grey-1">
          <div class="row justify-center">
                <q-card flat class="col-12">
                    <div class="row">
                        <q-card-section class="col-6 bg-grey-1">
                           <div class="text-h4 text-weight-bold q-my-lg">
                               Covid Watch
                           </div>
                           <q-card>
        <q-tabs
          v-model="tab"
          dense
          class="text-grey"
          active-color="primary"
          indicator-color="primary"
          align="justify"
          narrow-indicator
        >
          <q-tab name="mails" label="All Posts" />
          <q-tab name="next" label="Posts from Africa" />
          <q-tab name="other" label=" Posts from around the world" />
          
        </q-tabs>

        <q-separator />

        <q-tab-panels v-model="tab" animated>
          <q-tab-panel name="mails">
             <!-- External content goes here -->
           <q-card flat>
               <q-card-section>
                   
               </q-card-section>
           </q-card>
          </q-tab-panel>

          
        </q-tab-panels>
      </q-card>

       
                        </q-card-section>
                         <q-card-section class="col-3 bg-white">
                           <div class="text-h6 text-weight-bold q-my-lg">
                               Resources
                           </div>
                            <q-card flat bordered>
                               <q-toolbar class="bg-grey-1 q-my-md">
                                   
                                       OFFICIAL COVID-19 BOT FROM WHO
                                   
                               </q-toolbar>
                               <q-card-section>
                                   
                                   
This is the official verified Covid-19 Whatsapp bot from the World Health Organization(WHO) to give you information and facts on Covid-19
                               </q-card-section>
                               <q-card-actions>
                                   <q-btn outline type="a" target="_blank" href="" label="send-message" />
                               </q-card-actions>
                            </q-card>

                             <q-card flat bordered>
                               <q-toolbar class="bg-grey-1">
                                   
                                       Fact Check Africa
                                   
                               </q-toolbar>
                               <q-card-section>
                                   
                                   If the information you receive sounds suspicious or inaccurate, we encourage you to double-check information with these official IFCN Fact Checking Organizations:
                               </q-card-section>
                            </q-card>
                        </q-card-section>
                         <q-card-section class="col-3 bg-grey-1">
                           <div class="text-h6 text-weight-bold q-my-lg">
                               Covid Stats
                           </div>
                            <q-card flat bordered>
                               <q-img src="statics/covid19.jpg" />
                            </q-card>
                        </q-card-section>
                    </div>
                </q-card>
          </div>
      </div>
  </div>
</template>

<script>
export default {
  data(){
      return {
          tab: 'mails'
      }
  }
}
</script>

<style>

</style>