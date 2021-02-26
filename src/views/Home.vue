<template>
  <div class="home">
    <navBar/>
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue';
import navBar from "../components/navBar";

export default {
  name: 'Home',
  components: {
    HelloWorld,
    navBar,
  }
}
</script>
