<template>
<navbar></navbar>
  <router-view/>
<footerCom/>
</template>

<script>
  import navbar from './components/navbar.vue'
  import footerCom from './components/footerCom.vue'

  export default{
    name: 'App',
    components:{
      navbar,
      footerCom,
    }
  }
</script>

<style>
::-webkit-scrollbar {
    display: none;
}
body {
    background-color: #165945;
    color: #ED6B5B;
}
</style>

