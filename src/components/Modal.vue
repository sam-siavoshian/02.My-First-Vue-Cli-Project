<template>
  <div class="modalParent">
    <div class="modal">
      <h3 class="modal-title">Sam Siavoshian</h3>
      <p class="modal-description">Front End Developer</p>
    </div>
  </div>
</template>

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
    padding: 20px;
    border-radius: 10px;
    background-color: crimson;
    margin: 100px auto;
  }
  .modal-title {
    color: #fff;
  }
  .modal-description {
    color: #fff;
  }
</style>