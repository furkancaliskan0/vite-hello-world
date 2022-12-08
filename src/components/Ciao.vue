<script>
export default {
   // name: "Ciao",
    data () {
        return{
            saluto: "Ciao a tutti dal componente!"
        }
    }
}

</script>

<template>
  <h1>{{ saluto }}</h1>

  
</template>

<style scoped>
h1 {
  background-color: yellow;
  color: crimson;
}
</style>
