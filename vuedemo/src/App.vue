<template>
<div>
  <h1>{{titulo}}</h1>
<img v-bind:src="foto.url" v-bind:alt="foto.titulo">
</div>
</template>

<script>
export default {
  data(){
    return{
      titulo: 'VueJs Demo',
      foto : {
        url :  "https://www.clubeparacachorros.com.br/wp-content/uploads/2018/07/cachorros-mais-fofos-do-mundo-lulu-da-pomerania-filhote.jpg",
        titulo : "cachorro fofo"
      }
    }
  }
}
</script>

<style>

</style>
