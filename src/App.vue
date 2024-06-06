<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png">-->
  <h1>{{ title }}</h1>
  <Modal :jovic = "header" />
</template>

<script>

import Modal from './components/Modal.vue';

export default { // this is a comonet object
  name: 'App', // name of the component
   components: {
  //registering the extra components you are using on the compoent page
      Modal
   },
    
  data(){
    return{
      title: 'myfirst vue app',
      header: 'hellow from modal and am passing on a prop having an attribute called jovic',
    }
  }

}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
