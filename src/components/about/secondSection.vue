<template>
  <div>
    <q-card>
      <q-card-section class="text-weight-bold text-center">
              EGI PARTNERS
          </q-card-section>
    </q-card>
     <q-card v-for="(partner,index) in partners" :key="index" class="row justify-center">
          
          <q-card-section class="col-12">
            <q-card bordered class="row">
              <div class="col-2 bg-grey-1">
                  <q-img :src="partner.img" style="width:150px; height:150px"/>
              </div>
              <q-card-section class="col-9">
                  <q-toolbar class="bg-blue-grey-10 justify-center text-white">
                    <q-toolbar-title class="row justify-center">
                      {{partner.title}}
                    </q-toolbar-title>
                  </q-toolbar>
                  <div>
                     {{partner.details}}
                  </div>
              </q-card-section>
              <q-card-section class="col-1 justify-center  bg-grey-2">
                <div v-for="(link,index) in partner.links" :key="index" >
                    <q-btn flat round icon="language" :href="link"  type="a" target="_blank"   />
                </div>
                 
                  
              </q-card-section>
            </q-card>
          </q-card-section>
     </q-card>
  </div>
</template>

<script>
export default {
   data(){
     return{
       partners:[
         {
           img: 'statics/pl1.png',
           title:'UDUGU',
           details:'UDUGU will be overall EGI Consortium lead, provide quality assurance support, and lead national-level Policy Engagement and Dialogues for enhanced capacity to promote job creatio for youth. Udugu will provide strategic oversight and guidance to generate maximum synergy between the various EGI interventions. Follow the links for more details on UDUGU work...',
           links:[
                'https://udugu.org/','https://www.facebook.com/udugunexus/','https://twitter.com/LabCitizens'
           ]
         },
         {
           img: 'statics/pl2.png',
           title:'VISET',
           details:'VISET will improve informal sector voice and capacity on Rights literacy in support demands and solutions from informal sector players for greater accountability and constitutionalism in Zimbabwe. Follow the links for more details on VISET work ..',
           links:[
                'http://www.viset.org.zw/','https://www.facebook.com/Vendors-Initiative-for-Social-and-Economic-Transformation-VISET-773349322705983/','https://twitter.com/visetinfo'
           ]
         },
         {
           img: 'statics/pl3.png',
           title:'YETT',
           details: 'YETT will tackle issues of limited access to information, knowledge and capacity on economic constitutional rights and policies, including devolution in order to remove hinderances to youth participation in economic governance. Follow links for more info on YETT work ...',
           links:[
                'http://www.viset.org.zw/','https://www.facebook.com/Vendors-Initiative-for-Social-and-Economic-Transformation-VISET-773349322705983/','https://twitter.com/visetinfo'
           ]
         },
         {
           img: 'statics/pl4.png',
           title:'TIZ',
           details:'TIZ will focus on governance transparency and accountability in the government procurement process to reduce both corruption and the risk of building corruption into devolved governance structures and systems. Follow links for more details on TIZ work ...', 
            links:[
                'http://www.viset.org.zw/','https://www.facebook.com/Vendors-Initiative-for-Social-and-Economic-Transformation-VISET-773349322705983/','https://twitter.com/visetinfo'
           ]
         },
         {
           img: 'statics/pl5.png',
           title:'ZIMCODD',
           details: 'ZIMCODD will address issues of capacities in local tiers of government in the efficient management of public finances (including public debt) in order to improve public service delivery and local economic development; and empower citizens in their communities to demand accountability and transparency from local government authorities as duty bearers. Follow links for more details on ZIMCOD work...',
           links:[
                'http://www.viset.org.zw/','https://www.facebook.com/Vendors-Initiative-for-Social-and-Economic-Transformation-VISET-773349322705983/','https://twitter.com/visetinfo'
           ]
         },

       ]
     }
   }
}
</script>

<style>

</style>