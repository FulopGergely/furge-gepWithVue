<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" /> <!--  ezt importáljuk -->
  </div>
</template>

<!--  html comment -->

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue"; //  ezt a componens mappánál definiáljuk

export default { //elérhetővé teszi hgoy mindenhol használhassuk amit itt leírunk
  name: "Home",
  components: { //home gyerekei
    HelloWorld,
  },
};
</script>


<style scoped>
/* scoped: csak erre a componensre használja */


</style>
