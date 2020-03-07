<template>
<div>
  <Homepage />
  
</div>
  
</template>

<script>
import Homepage from "./components/Homepage/Homepage"


export default {
  name: 'app',
  components: {
     Homepage
  },

}
</script>

<style>
 * {
   box-sizing: border-box;
   margin: 2px;
   padding: 0;
   }
   body {
     line-height: 1.4;
     }


</style>
