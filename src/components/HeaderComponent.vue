<template>
  <div class="container">
    <img src="../assets/logo.png" alt="logo.png" height="120%" />
    
    <div class="menucontainer ">
      <a href="#">home</a>
      <a href="#">about us</a>
      <a href="#">contact us</a>
    </div>
    
    <div class="cotainer-button">
      <button type="submit">signup</button>
    </div>
  </div>
</template>

<script>

export default {
  name: 'HeaderComponent',

};
</script>

<style>
.container {
  width: 100%;
  height: 4rem;
  padding: 1rem;
  align-items: center;
  background-color: skyblue;
  display: flex;
  justify-content: space-between;
}

.menucontainer {
  padding: 5px;
  margin-top: 0px;
  text-align: right;
  text-decoration: none;
  display: flex;
  gap: 2rem;
}
</style>
