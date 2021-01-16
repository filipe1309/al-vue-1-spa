<template>
  <button class="botao botao-perigo" :type="tipo">{{ rotulo }}</button>
</template>

<script>
export default {
  props: ['tipo ', 'rotulo']
}
</script>

<style>
  .botao {
    display: inline-block;
    padding: 10px;
    border-radius: 3px;
    margin: 10px;
    font-size: 1.2em;
  }

  .botao-perigo {
    background-color: firebrick;
    color: white;
  }

  .botao-padrao {
    background-color: darkcyan;
    color: white;
  }

</style>