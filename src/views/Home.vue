<template>
  <div class="home">
  <DogHeader />
  <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import DogHeader from "@/components/DogHeader.vue";

export default {
  name: "Home",
  components: {
    DogHeader,
    HelloWorld
  }
};
</script>
