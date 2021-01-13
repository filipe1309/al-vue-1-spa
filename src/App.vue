<template>
  <div>
    <h1>{{ titulo }}</h1>

    <ul>
      <li v-for="foto of fotos"><img v-bind:src="foto.url" :alt="foto.titulo">  </li>
    </ul>
    
  </div>
</template>

<script>
export default {
  data() {
    return {
      titulo: 'Alurapic',
      fotos: [
        {
          url: 'https://amoraospets.com/wp-content/uploads/2019/01/dachshund.jpg',
          titulo: 'cachorro'
        },
        {
          url: 'https://amoraospets.com/wp-content/uploads/2019/01/dachshund.jpg',
          titulo: 'cachorro2'
        }
      ]
    }
  }
}
</script>

<style>

</style>
