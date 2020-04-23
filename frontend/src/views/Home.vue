<template>
  <v-app>
    <v-img
      :aspect-ratio="16 / 9"
      src="@/../public/home.jpg"
      class="white--text"
    >
      <v-container style="height: 100%">
        <v-row class="py-3">
          <div class="headline font-italic">Jan-Code & VD</div>
        </v-row>
        <v-spacer style="height: 30%"></v-spacer>
        <v-row class="py-3 px-11">
          <div class="display-3">全栈开发之路</div>
        </v-row>
        <v-row class="py-3 px-12">
          <div class="body-1">Vue-Vuetify / Node-Express</div>
        </v-row>
        <v-row class="py-12 px-10">
          <v-col md="2">
            <v-btn rounded color="#004D40" width="120" class="white--text"
              >合作入口
            </v-btn>
          </v-col>
          <v-col md="2">
            <v-btn rounded color="#004D40" width="120" class="white--text"
              >用户入口
            </v-btn>
          </v-col>
        </v-row>
      </v-container>
    </v-img>

    <my-footer />
  </v-app>
</template>

<script>
export default {
  name: "Home",
  components: {
    MyFooter: () => import("@/components/MyFooter")
  },
  data: () => ({})
};
</script>
