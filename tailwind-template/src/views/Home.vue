<template>
  <div class="home">
    <img class="mx-auto" alt="Vue logo" src="../assets/logo.png" />
    <h1 class="text-blue-500 bg-red-500">TEST</h1>

    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  components: {
    HelloWorld,
  },
};
</script>
<style lang="postcss" scoped></style>
