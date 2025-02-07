<template>
  <nav class="navbar">
    <div class="nav-links">
      <a href="#">Home</a>
      <a href="#">Features</a>
      <a href="#">Pricing</a>
      <a href="#">Our Team</a>
      <a href="#">Contact</a>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=DM+Sans:wght@100..1000&display=swap');

.navbar {
  font-family: "DM Sans", sans-serif;
  display: flex;
  justify-content: center;
  align-items: center;
  position: absolute; 
  top: 0;
  left: 0;
  width: 100%;
  padding: 15px 0;
  z-index: 100; 
  margin-top: 85px;
}

.nav-links {
  display: flex;
  gap: 40px;
}

a {
  color: white;
  text-decoration: none;
  font-size: 18px;
  transition: color 0.3s ease;
}

a:hover {
  color: #f39c12;
}
</style>
