<template>
 <div>
<son></son>
<fir></fir>
<Lo></Lo>
 </div>
</template>

<script>
import son from '../components/home/son'
import axios from "../../src/assets/axios"
import Fir from "../components/home/Fir"
import Lo from  "../components/home/Lo"
 export default {
   name: '',
   props: {
   },
   components: {
     son,
     Fir,
     Lo

   },
   data () {
     return {

     }
   },
   methods: {

   },
   mounted() {

   },
   watch: {

   },
   computed: {

   }
 }
</script>

<style scoped lang='scss'>

</style>