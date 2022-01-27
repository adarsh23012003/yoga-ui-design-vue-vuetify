<template>
  <v-card class="py-12" flat height="700px" color="bg">
    <v-row>
      <v-col cols="12" md="6" class="my-auto">
        <v-container>
          <h1 class="display-2 font-weight-medium pl-5 d-flex justify-start">
            ENR where magic happens
          </h1>
          <p class="py-5 pl-5 d-flex justify-start">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Alias
            laudantium magnam nihil tempore. Cumque assumenda magnam a quasi
            fugiat minima!
          </p>
          <v-btn class="my-5 ml-6 px-10 py-5" color="error" rounded
            >Subscribe</v-btn
          >
        </v-container>
      </v-col>
      <v-col cols="12" md="6" class="my-auto"
        ><v-img src="@/assets/img/heroimg.png"></v-img
      ></v-col>
    </v-row>
  </v-card>
</template>

<script>
export default {
  data: () => ({
    cards: [
      {
        src: "https://cdn.vuetifyjs.com/images/cards/road.jpg",
      },
      {
        src: "https://cdn.vuetifyjs.com/images/cards/plane.jpg",
      },
    ],
  }),
};
</script>

<style scoped>
</style>