<template>
  <div>
    <h1>{{ titulo }}</h1>
    <img v-bind:src="foto.url" :alt="foto.titulo">  
  </div>
</template>

<script>
export default {
  data() {
    return {
      titulo: 'Alurapic',
      foto: {
        url: 'https://amoraospets.com/wp-content/uploads/2019/01/dachshund.jpg',
        titulo: 'cachorro'
      }
    }
  }
}
</script>

<style>

</style>
