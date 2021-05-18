<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <Adowan msg="Adowan" />
  </div>
</template>

<script>
// @ is an alias to /src
import Adowan from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  components: {
    Adowan,
  },
};
</script>
