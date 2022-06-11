<template>
  <nav>
    <li class="logo"></li>
    <div class="links">
      <Router-link to="/home">Home</Router-link>
      <Router-link to="/about">About</Router-link>
      <Router-link to="/Tech-Stack">Tech Stack</Router-link>
      <Router-link to="/Projects">Projects</Router-link>
      <Router-link to="/Contact">Contact</Router-link>
    </div>
  </nav>
  <router-view />
</template>

<style lang="scss">
nav{
  display: flex;
  justify-content: space-between;
}
li{
  list-style: none;
}
a{
  text-decoration: none;
  margin-left: 67px;
  color: #000;
}
a:first-child{
  margin-left: 0;
}

</style>
