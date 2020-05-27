<template>
<div>
 <Home/>
  <Interest/>
  <Work/>
  <OtherInterest/>
  <Connect/>
</div>
</template>

<script >



import Home from "@/views/Home.vue"
import Interest from "@/views/Interest.vue"
import Connect from "@/views/Connect.vue"
import Work from "@/views/Work.vue"
import OtherInterest from "@/views/OtherInterest.vue"





export default {
  components:{
    Home,Interest,Connect,Work,OtherInterest
  },meta:{metaTags:[

    {name:'viewport',content:'width=device-width, initial-scale=1.0'}
  ]}
  }


</script>
<style scoped>
</style>>

