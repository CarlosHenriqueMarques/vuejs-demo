<template>
<div>
  <h1 v-text="titulo"></h1>
   
   
   <ul>
     <li v-for="foto of fotos">
        <img :src="foto.url" :alt="foto.titulo  ">
     </li>
   </ul>
   
   
</div>
</template>

<script>
export default {
  data(){
    return{
      titulo: 'VueJs Demo',
      fotos : [ 
        {
          url :  "https://www.clubeparacachorros.com.br/wp-content/uploads/2018/07/cachorros-mais-fofos-do-mundo-lulu-da-pomerania-filhote.jpg",
          titulo : "cachorro fofo"
        },
        {
          url :  "https://www.clubeparacachorros.com.br/wp-content/uploads/2018/07/cachorros-mais-fofos-do-mundo-lulu-da-pomerania-filhote.jpg",
          titulo : "cachorro fofo2"
        }
      ] 
    }
  }
}
</script>

<style>

</style>
