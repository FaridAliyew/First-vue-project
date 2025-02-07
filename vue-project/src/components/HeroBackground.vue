<template>
  <div class="hero-container">
    <div class="overlay"></div>
    <slot></slot>
  </div>
</template>

<style scoped>
.hero-container {
  background-image: url('../images/Image.png');
  height: 100vh;
  background-size: cover;
  background-position: center;
  display: flex;
  flex-direction: column;
  align-items: center;
  position: relative;
  overflow: hidden;
}

.overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgb(44, 1, 105); 
  z-index: -1; 
}


</style>
