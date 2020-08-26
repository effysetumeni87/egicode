<template>
  <div class="row">
      <div class="col-12 kustify-center bg-blue-grey-1">
          <div class="row justify-center">
                <q-card flat class="col-10">
                    <div class="row">
                        <q-card-section class="col-8 bg-grey-1">
                           <div class="text-h4 text-weight-bold q-my-lg">
                               PUBLICATIONS
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
          <q-tab name="mails" label="All" />
          <q-tab name="alarms" label="Reports" />
          <q-tab name="movies" label="Policy Briefs" />
        </q-tabs>

        <q-separator />

        <q-tab-panels v-model="tab" animated>
          <q-tab-panel name="mails">
             
             Comming Soon
          </q-tab-panel>

          <q-tab-panel name="alarms">
             
            Comming Soon
          </q-tab-panel>

          <q-tab-panel name="movies">
             
            Coming Soon
          </q-tab-panel>
        </q-tab-panels>
      </q-card>

       
                        </q-card-section>
                         <q-card-section class="col-4 bg-grey-2">
                           <div class="text-h4 text-weight-bold q-my-lg">
                               Social Media
                           </div>
                            <q-card flat bordered>
                               <q-toolbar class="bg-grey-1">
                                   <q-toolbar-title>
                                       Facebook
                                   </q-toolbar-title>
                               </q-toolbar>
                               <q-card-section>
                                   <q-separator inset />
                               </q-card-section>
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