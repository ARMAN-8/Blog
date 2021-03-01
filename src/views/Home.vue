<template>
  <div class="home">
    <navBar/>
    <mainPageContent/>
  </div>
</template>
<script>
// @ is an alias to /src
import navBar from "../components/navBar";
import mainPageContent from "../components/content/mainPageContent";

export default {
  name: 'Home',
  components: {
    navBar,
    mainPageContent,
  }
}
</script>
