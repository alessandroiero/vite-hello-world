<!-- contiene js -->
<script>
// dobbiamo esportarlo per poterlo importare
  export default {
    data(){
      return{
        message: "La mia prima app con Vite"
      }
    }
  }
</script>

// <!-- contiene html -->
<template>
    <h1>{{ message }}</h1>
    <p>Paragrafo componenti</p>
</template>

// <!-- contiene css -->
<style scoped>
p{
  color: red;
}</style>