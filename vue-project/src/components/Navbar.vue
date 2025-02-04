<template>
  <nav>
    <a href="#">Home</a>
    <a href="#">Features</a>
    <a href="#">Pricing</a>
    <a href="#">Our Team</a>
    <a href="#">Contact</a>
  </nav>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=DM+Sans:ital,opsz,wght@0,9..40,100..1000;1,9..40,100..1000&family=Itim&family=Marcellus&family=Overpass:ital,wght@0,100..900;1,100..900&family=PT+Sans:ital,wght@0,400;0,700;1,400;1,700&family=Playfair+Display:ital,wght@0,400..900;1,400..900&display=swap');

nav{
    font-family: "DM Sans", serif;
    display: flex;
    justify-content: center;
    margin-top: 85px;
    /* border: solid 2px; */
}

a {
  color: black;
  text-decoration: none;
  font-size: 18px;
  margin-right: 40px;
}
</style>
