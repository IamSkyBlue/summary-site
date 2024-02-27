<template>
  <v-app>
    <v-card color="blue-darken-4">
      <v-card-title class="text-center justify-center text-h3 mt-5 py-5"
        ><v-avatar size="100" class="text-center justify-center mb-7"
          ><v-img class="pt-5" src="@/assets/self.jpg"></v-img
        ></v-avatar>
        <br />
        魏敏皓
      </v-card-title>
      <v-card-subtitle class="text-center justify-center text-h5 py-3"
        >國立臺灣海洋大學資工系碩士</v-card-subtitle
      >
      <v-tabs v-model="tab" fixed-tabs>
        <v-tab value="one">參與專案</v-tab>
        <v-tab value="two">其他經歷</v-tab>
      </v-tabs>
    </v-card>
    <v-sheet color="blue-lighten-4">
      <v-container max-width="80%">
        <v-card-text>
          <v-window v-model="tab">
            <v-window-item value="one"> <ProJect /> </v-window-item>
            <v-window-item value="two"> <Exps /> </v-window-item>
          </v-window>
        </v-card-text>
      </v-container>
    </v-sheet>
    <Footer />
  </v-app>
</template>

<script>
import ProJect from "./components/ProJect.vue";
import Exps from "./components/Exps.vue";
import Footer from "./components/Footer.vue";
export default {
  data: () => ({
    tab: null,
  }),
};
</script>