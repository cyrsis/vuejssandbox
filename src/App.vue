<template>
  <div id="app">
    <img class="logo" src="./assets/logo.png">
    <router-view></router-view>
  </div>
</template>

<script>
import Firebase from 'firebase'

let config={
  apiKey: "AIzaSyBQ6FZfyzpyICkXTf60o3TU3H39DkWJCq4",
  authDomain: "onpaper-9c248.firebaseapp.com",
  databaseURL: "https://onpaper-9c248.firebaseio.com",
  projectId: "onpaper-9c248",
  storageBucket: "onpaper-9c248.appspot.com",
  messagingSenderId: "665577702717"
}
export default {
  name: 'app'
}
</script>

<style>
#app {
  background:#16a085;
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  margin-top: 60px;
}
  .logo{
    height: 80px;
    width: 120px;

  }
</style>
