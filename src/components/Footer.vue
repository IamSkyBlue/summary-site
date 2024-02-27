<template>
  <v-footer class="text-center d-flex flex-column" color="blue-darken-4">
    <v-btn
      class="justify-center mt-3"
      color="surface"
      icon="mdi-email"
      href="mailto:bob890823@gmail.com"
    ></v-btn>
    <br />
    <v-text>Made with ❤️ by IamSkyBlue</v-text>
  </v-footer>
</template>

<script setup>
const icons = ["mdi-facebook", "mdi-twitter", "mdi-linkedin", "mdi-instagram"];
</script>

<script>
export default {
  data: () => ({
    icons: ["mdi-facebook", "mdi-twitter", "mdi-linkedin", "mdi-instagram"],
  }),
};
</script>