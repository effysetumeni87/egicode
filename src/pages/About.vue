<template>
  <div class="row">
      <div class="col-12 kustify-center bg-blue-grey-1">
          <div class="row justify-center">
<q-card flat class="col-10">
             <first-section class="q-ma-sm" />
             <second-section />
           </q-card>
          </div>
           
      </div>    
  </div>
</template>

<script>
import firstSection from "../components/about/firstSection"
  import secondSection from "../components/about/secondSection"
//   import thirdSection from "../components/home/thirdSection"
//   import fourthSection from "../components/home/fourthSection"
export default {
 components: {
     firstSection,
     secondSection,
    //   thirdSection,
    //   fourthSection
    //  footerSection
  },
}
</script>

<style>

</style>