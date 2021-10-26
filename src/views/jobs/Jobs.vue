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
       {title:'coco bohdan', id: 4, details: 'bohdan'},
       {title:'kit', id: 4, details: 'bohdan'},
       {title:'like', id: 4, details: 'bohdan'}
     ]
   }
 }
};
</script>

<style scoped>

</style>
