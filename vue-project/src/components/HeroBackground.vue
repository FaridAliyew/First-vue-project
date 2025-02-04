<template>
    <div class="background-image" :style="{ backgroundImage: `url(${imageUrl})` }"></div>
  </template>
  
  <script>
  export default {
    props: {
      imageUrl: {
        type: String,
        required: true,
      },
    },
  };
  </script>
  
  <style scoped>
  .background-image {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-size: cover;
    background-position: center;
    z-index: -1; /* Digər elementlərin arxasında qalması üçün */
  }
  </style>