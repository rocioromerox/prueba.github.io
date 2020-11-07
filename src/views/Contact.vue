<template>
  <h2>Contacto
      <p>{{message}}</p>
  </h2>
      <Formulario/>
  
  
</template>

<script>
import Formulario from '../components/Formulario';

export default {
    name: 'Contact',
    components : {
        Formulario
    },

    data (){
        return {
            message: 'Formulario Contacto',
        }
    }
}
</script>

<style lang="scss"> 

h2 {
    color: red;

    & p {
        color: blue;
    }
}

</style>