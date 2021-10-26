<template>
<h1>Jobs</h1>
  <div v-for="job in jobs" :key="job.id">
    <h2>{{job.title}}</h2>
  </div>
</template>

<script>
export default {
 data () {
   return {
     jobs: [
       {title:'coco bohdaknbn', id: 1, details: 'bohdan'},
       {title:'kit', id: 2, details: 'bohdan'},
       {title:'like', id: 3, details: 'bohdan'}
     ]
   }
 }
};
</script>

<style scoped>

</style>
