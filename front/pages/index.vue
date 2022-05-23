<template>
<div>
  <!-- <v-row justify="center" align="center"> -->
  <link href="https://fonts.googleapis.com/css?family=Sawarabi+Mincho" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css?family=M+PLUS+Rounded+1c" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css?family=Sawarabi+Mincho" rel="stylesheet">
    <!-- <v-col cols="12" sm="10" md="6"> -->
      <AboutMe />
      <Works />
      <Activities />
      
    <!-- </v-col> -->
  <!-- </v-row> -->
  </div>
</template>

<script>
export default {

}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Caveat&display=swap');

.v-main__wrap {
  background:url("~/assets/img/back.png") center center / cover no-repeat fixed;
  width: 100%;
  height: 100%;
  background-color: rgba(255, 255, 255, 0.562);
}
h1 {
  font-size: 60px;
  margin: 80px;
  text-align: center;
  color: #BF4E1A;
  font-family: 'Caveat', cursive;
}
h2 {
  font-size: 19px;
  padding-bottom: 8px;
  color: #BF4E1A;
  font-family: "Sawarabi Mincho";
}
h3 {
  font-size: 15px;
  margin-bottom: 4px;
  font-family: "Sawarabi Mincho";
}
p {
  font-size: 14.5px;
  /* font-family: "Sawarabi Mincho"; */
  /* font-family: "M PLUS Rounded 1c"; */
  /* font-family: "Sawarabi Mincho"; */
  font-family: serif;
  font-weight: 300;
}
</style>
