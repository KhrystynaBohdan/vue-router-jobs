<template>
<h1>job details page</h1>
  <p>the job id is {{id}}</p>
</template>

<script>
export default {
  data () {
  return {
    id: this.$route.params.id
  }
  }
};
</script>

<style scoped>

</style>
