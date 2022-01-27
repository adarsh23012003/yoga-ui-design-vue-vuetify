<template>
  <v-app>
    <v-app-bar app elevation="0">
      <h2 class="red--text">LOGO</h2>
      <v-spacer></v-spacer>
      <router-link
        v-for="(link, i) in links"
        :key="i"
        :to="link.path"
        class="mr-5 black--text"
        >{{ link.name }}</router-link
      >

      <v-btn rounded dark color="red" class="ml-5 px-10" to="/login"
        >Sign Up</v-btn
      >
    </v-app-bar>
    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      links: [
        {
          path: "/",
          name: "Home",
        },
        {
          path: "/about",
          name: "About",
        },
        {
          path: "/shop",
          name: "Shop",
        },
        {
          path: "/contact",
          name: "Contact us",
        },
      ],
    };
  },
};
</script>
<style >
a {
  text-decoration: none;
}
</style>