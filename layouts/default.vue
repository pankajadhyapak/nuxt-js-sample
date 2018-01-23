
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

</style>
