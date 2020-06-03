<template>
 <div>
<div class="lou">
<div class="lou1">楼+  实战课程 |  
<div class="lou2">定期开班，导师助教全程辅导，最快最优成长</div>
<div class="lou3">更多></div>
</div>
  
  </div>

 </div>
</template>

<script>
 export default {
   name: '',
   props: {
   },
   components: {

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

.lou{
  border: 1px solid  red;
  width: 1510px;
  height: 300px;

}
.lou1{
  font-size: 22px;
 position: relative;
 margin-left: 200px;
margin-top: 30px;
cursor: pointer;
}
.lou2{
  position: absolute;
  font-size: 15px;
margin-left: 150px;
bottom: 1px;
color: rgb(102,124,180);
cursor: pointer;
}

.lou3{
   position: absolute;
  margin-left: 1000px;
  color: rgb(106,106,162);
  font-size: 16px;
  bottom: 1px;
  cursor: pointer;
}
</style>