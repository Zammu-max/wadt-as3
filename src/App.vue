<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png" /> -->
  <img id="imgOne" src="./assets/img1.jpeg" alt="authors with friends">
  <p id="desc">Hello my name is Muazzam and im currently studying Web Development in Politeknik Brunei. In my free time i like to workout, play games and learn how to code. </p>
  <br><br><br>
  <HelloWorld msg="Powered Vue 3 + Vite" />
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

#imgOne{
  margin-left: auto;
  margin-right: auto;
  width: 400px;
  height: 350px;
}

#desc{
  margin-left: auto;
  margin-right: auto;
  width: 50%;
}
</style>
