<template>
<div>
 <first-section />
 <second-section/>
  <third-section/> 
  <fourth-section/>
  <!-- <footer-section/>  -->  
</div>
</template>

<script>
import firstSection from "../components/home/firstSection"
 import secondSection from "../components/home/secondSection"
  import thirdSection from "../components/home/thirdSection"
  import fourthSection from "../components/home/fourthSection"
// import footerSection from "../components/footerSection"
export default {
  components: {
     firstSection,
      secondSection,
      thirdSection,
      fourthSection
    //  footerSection
  },
  name: 'PageIndex'
}
</script>
