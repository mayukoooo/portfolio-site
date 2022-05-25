<template>
<div>
      <Header/>
      <AboutMe />
      <Works />
      <Activities />
  </div>
</template>

<script>
export default {

}
</script>

<style>
/* @import url('https://fonts.googleapis.com/css2?family=Caveat&display=swap'); */
@import url('https://fonts.googleapis.com/css2?family=Itim&display=swap');

.container {
  margin: 20px 150px;
}
.v-main__wrap {
  background:url("~/assets/img/back.png") center center / cover no-repeat fixed;
  width: 100%;
  height: 100%;
  /* background-color: #FFF9F2; */
}
h1 {
  font-size: 40px;
  margin-top: 100px;
  margin-bottom: 70px;
  text-align: center;
  /* color: #BF4E1A; */
  /* font-family: 'Caveat', cursive; */
  /* font-family: serif; */
  font-family: sans-serif;
  font-style: italic;
  /* color: rgb(78, 236, 183); */
  color: #FF9C69;
  font-family: 'Itim', cursive;
}
h2 {
  font-size: 19px;
  padding-bottom: 8px;
  /* color: #BF4E1A; */
  /* font-family: serif; */
  font-family: sans-serif;
  font-weight: 900;
  /* color: #504E4E; */
}
h3 {
  font-size: 15px;
  margin-bottom: 4px;
  /* font-family: serif; */
  font-family: sans-serif;
  font-weight: 700;
  /* color: #504E4E; */
}
h4 {
  font-size: 15px;
  margin-bottom: 10px;
  font-weight: normal;
  font-style: italic;
  /* font-family: serif; */
  font-family: sans-serif;
  /* color: #504E4E; */
}
p {
  font-size: 14.4px;
  /* font-family: serif; */
  font-family: sans-serif;
  font-weight: 500;
  /* color: #504E4E; */
}
a {
  color: blue;
  font-weight: bold;
}
</style>
