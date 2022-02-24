<template>
  <div class="modalParent" @click="closeModal">
    <div class="modal">
      <h3 class="modal-title">Sam Siavoshian</h3>
      <p class="modal-description">Front End Developer</p>
    </div>
  </div>
</template>

<script>

export default {
  methods: {
    closeModal () {
      this.$emit('close')
    }
  },
}

</script>

<style>
  .modalParent {
    top: 0;
    position: fixed;
    background-color: rgba(0, 0, 0, 0.5);
    width: 100%;
    height: 100%;
  }
  .modal {
    width: 400px;
    padding: 50px;
    border-radius: 10px;
    background-color: #41B883;
    margin: 100px auto;
  }
  .modal-title {
    color: #fff;
  }
  .modal-description {
    color: #fff;
  }
</style>