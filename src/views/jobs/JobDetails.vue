<template>
  <h1>Job Details Page</h1>
  <p>The job id is {{ id }}</p>
</template>

<script>
export default {
    props: ['id'],
    // data(){
    //     return{
    //         // id from router index.js
    //         id: this.$route.params.id
    //     }
    // }
}
</script>

<style>

</style>