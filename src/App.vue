<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png">-->
  <h1>{{ title }}</h1>
  <Modal/>
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
      title: 'myfirst vue app'
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
