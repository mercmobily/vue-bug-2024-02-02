<script setup>
import RecordPlain from "./RecordPlain.vue"
const iExist = { name: "Tony", descriptions: "Test" }

// Only when using the router, :record="iDoNotExist" will trigger a nasty error:
//  Unhandled error during execution of scheduler flush. This is likely a Vue internals bug. Please open an issue at https://github.com/vuejs/core . 
// When not using the router, the error doesn't show

</script>

<template>
 <layout-div>
    <h2 class="text-center mt-5 mb-3">projects</h2>
      <div class="card-body">
      <!--<RecordPlain :record="iExist"/>-->
      <RecordPlain :record="iDoNotExist"/>
      </div>
  </layout-div>   

</template>


<style>
</style>
