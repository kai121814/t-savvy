<template>
  <div class="topnav">
    <a class="active" href="#home">Home</a>
    <a href="#news">News</a>
    <a href="#contact">Contact</a>
    <a href="#about">About</a>
  </div>
</template>

<style scoped>
/* background for navbar */
.topnav {
  overflow: hidden;
  background-color: #BAD38F;
  border-radius: 5px;
}

/* navbar content */
.topnav a {
  float: left;
  color: #000;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
  text-transform: uppercase;
  font-weight: 700;
  font-family: sans-serif;
}

/* navbar hover */
.topnav a:hover {
  background-color: #869769;
  color: black;
}

</style>