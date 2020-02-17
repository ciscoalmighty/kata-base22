<template>
  <div class="home">
    <DogHeader />
    <Volunteers />
    <ProgramTabs />
    <Contactus />
  </div>
</template>

<script>
// @ is an alias to /src

import DogHeader from "@/components/DogHeader.vue";
import Volunteers from "@/components/Volunteers.vue";
import ProgramTabs from "@/components/ProgramTabs.vue";
import Contactus from "@/components/Contactus.vue";

export default {
  name: "Home",
  components: {
    DogHeader,
    Volunteers,
    ProgramTabs,
    Contactus
  }
};
</script>
