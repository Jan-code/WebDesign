<template>
  <v-footer>
    <v-container fluid>
      <v-row>
        <v-col md="2" offset-md="1">
          <div class="font-weight-bold body-1">咨询</div>
          <div class="font-weight-light body-2">平台介绍</div>
          <div class="font-weight-light body-2">帮助中心</div>
        </v-col>
        <v-col md="2">
          <div class="font-weight-bold body-1">推广</div>
          <div class="font-weight-light body-2">招商合作</div>
          <div class="font-weight-light body-2">业务推荐</div>
        </v-col>
      </v-row>
      <v-row>
        <v-col offset-md="1">
          <div class="font-weight-light caption">
            Copyright &copy; Jan-Code {{ new Date().getFullYear() }}
          </div>
        </v-col>
      </v-row>
    </v-container>
  </v-footer>
</template>

<script>
export default {
  name: "MyFooter",
  data: () => ({})
};
</script>
