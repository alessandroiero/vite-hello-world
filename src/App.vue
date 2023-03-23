<script >
  // importiamo i componenti
  import AppTitle from "./components/AppTitle.vue"


  // componenti
  export default {
    components : {
      AppTitle
    }
  }
</script>

<template>
  <AppTitle></AppTitle>
  <AppTitle></AppTitle>
  <p>paragrafo app</p>
</template>

<style scoped>
p{
  color: green;
}

</style>
