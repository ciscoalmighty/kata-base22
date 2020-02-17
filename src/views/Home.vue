<template>
  <div class="home">
    <DogHeader />
    <Volunteers />
    <ProgramTabs />
  </div>
</template>

<script>
// @ is an alias to /src

import DogHeader from "@/components/DogHeader.vue";
import Volunteers from "@/components/Volunteers.vue";
import ProgramTabs from "@/components/ProgramTabs.vue";

export default {
  name: "Home",
  components: {
    DogHeader,
    Volunteers,
    ProgramTabs
  }
};
</script>
