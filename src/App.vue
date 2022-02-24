<template>
  <Nav/>
  <br>
  <div v-if="showModal">
    <Modal @close="changeModal"/>
  </div>
  <button class="showModal" @click="openModal">Show Modal</button>
  <br>
  <br>
  <h1>{{title}}</h1>
</template>

<script>
import Nav from './components/Nav.vue'
import Modal from './components/Modal.vue'

export default {
  name: 'App',
  components: {Nav,Modal},
  data () {
    return {
      title: "My Vue App",
      showModal: false,
    }
  },
  methods: {
    openModal() {
      this.showModal = true
    },
    changeModal() {
      this.showModal = !this.showModal
    },
  },
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
.showModal {
  width: 100px;
  height: 40px;
  background-color: #2c3e50;
  border-radius: 8px;
  color: white;
  cursor: pointer;
}
</style>
