<template>
  <nav>
    <ul>
      <li>About Us</li>
      <li>Shop</li>
      <li>Contanct Us</li>
    </ul>
  </nav>
</template>


<style>
nav {
  width: 100%;
  height: 90px;
  background-color: #41B883;
  position: relative;
  top: 0;
  left: 0;
}
ul {
  height: 100%;
  display: flex;
  justify-content: flex-end;
  align-items: center;
  list-style: none;
  margin: 0;
}
li {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  color: #2c3e50;
  margin-right: 20px;
  font-size: 24px;
  transition: all 0.3s;
}
li:hover {
  color: #fff;
}
</style>