<template>
  <div id="app">
    <div class="container-fluid">
      <news-api></news-api>
    </div>
    <div class="row justify-content-center mb-5">
      <div class="col mt-5" v-for="(item, index) of member" :key="index">
        <team-card v-bind:member="item" ></team-card>
      </div>
    </div>
  </div>
</template>

<script>
import NewsApi from './components/NewsApi.vue'
import TeamCard from './components/TeamCard.vue'

export default {
  
  name: 'App',

components:{
  TeamCard,
  NewsApi
},

  data(){
  return{
    member:[
      {
            codigo : 1 ,
      nombre : 'Andrés Arturo Anzola Gómez' ,
      descripcion : "Tecnológo en Diseño e Integración de Automatismos Mecatrónicos" ,
      rol : 'Desarrollador backend' ,
      image : "./Andres.jpg"
  
    },
    {
            codigo : 2 ,
      nombre : 'Cristian Camilo Castañeda Agudelo' ,
      descripcion : "Ingeniero Mecánico" ,
      rol : 'Scrum Master' ,
      image : './Cristian.jpg'
  
    },
    {
            codigo : 3 ,
      nombre : 'Diana María Ordoñez Almonacid' ,
      descripcion : "Ingeniera de Sistemas y Computación" ,
      rol : 'Product Owner' ,
      image : './Diana.jpg'
  
    },
    {
            codigo : 4 ,
      nombre : 'Julian Esteban Carvajal' ,
      descripcion : "Ingeniero de Sistemas" ,
      rol : 'Desarrollador backend' ,
      image : "./Julian.jpg"
  
    },
    {
            codigo : 5 ,
      nombre : 'Jeick Ruiz' ,
      descripcion : "Ingeniero de procesos químicos y bioquímicos" ,
      rol : 'Development Team' ,
      image : "./Imagen_JRuiz.jpg"
  
    }

    ]
  }


}}

</script>