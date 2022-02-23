<template>
  <Nav/>
  <br>
  <!-- <Modal/> -->
  <br>
  <h1>{{title}}</h1>
</template>

<script>
import Nav from './components/Nav.vue'
import Modal from './components/Modal.vue'

export default {
  name: 'App',
  components: {Nav},
  data () {
    return {
      title: "My Vue App"
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
}
</style>
