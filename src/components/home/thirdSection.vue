<template>
  <div >
    <q-parallax :height="200" :speed="0.5">
      <template v-slot:media>
        <img src="statics/blue-covid-banner.jpg">
      </template>
        <div class="text-h4 q-ma-md text-white text-bold">
           Covid-19 Watch
        </div>
      <q-btn label="learn more" color="white" outline rounded   to="/about" />
    </q-parallax>
  </div>
</template>


<script>
import myDivider from "../myDivider"
export default {
components: {
    myDivider
},
data(){
  return {}
      
}

}
</script>

<style>

</style>