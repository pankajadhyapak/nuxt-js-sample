
<template>
  <div>
    <navbar></navbar>
    <nuxt/>
    <agfooter></agfooter>
  </div>
</template>
<script>
  import navbar from '../components/navbar'
  import agfooter from '../components/footer'
  export default {
    components: {
      navbar,agfooter
    }
  }
</script>
<style>
  html {
    font-family: "Source Sans Pro", "Helvetica Neue", Arial, sans-serif;
  }
</style>
