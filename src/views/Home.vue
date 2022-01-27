<template>
  <div>
    <HeroCard />
    <v-card height="700px" color="warning"></v-card>
    <v-card height="700px" color="bg"></v-card>
  </div>
</template>

<script>
import HeroCard from "../components/HeroCard";

export default {
  name: "Home",

  components: {
    HeroCard,
  },
};
</script>
