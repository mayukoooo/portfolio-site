<template>
  <div class="header">
    <header>
    <h1>Mayuko's portfolio 🐈</h1>
    <nav class="nav">
      <ul class="menu-group">
        <li class="menu-item"><a href="#aboutMe">About me</a></li>
        <li class="menu-item"><a href="#works">Works</a></li>
        <li class="menu-item"><a href="#activities">Activities</a></li>
      </ul>
    </nav>
  </header>
  </div>
</template>

<script>
export default {

}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Itim&display=swap');
header {
  display: flex;
  align-items: center;
  margin: 0px 100px;
  font-size: 20px;
}
 
.title {
  margin-top: 0px;
  margin-bottom: 0px;
}
.header h1 {
  font-family: 'Itim', cursive;
  /* font-family: sans-serif; */
  font-size: 25px;
  margin: 0px;
}
.nav {
  margin-left: auto;
 }
 .menu-group li {
  /* font-family: serif; */
  /* font-family: sans-serif; */
  font-family: 'Itim', cursive;
  font-size: 25px;
  margin: 0px;
  color: #BF4E1A;
 }
.menu-item {
  list-style: none;
  display: inline-block;
  padding: 0px 10px;
}
.menu-item a {
  text-decoration: none;
}
</style>