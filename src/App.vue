<template>
  <!-- <layout> -->
  <router-view></router-view>
  <!-- </layout> -->
</template>

<script lang="ts">
import { Vue, Options } from "vue-class-component";

export default class AppComponent extends Vue {
  created() {
  }
}
</script>
<style>
@import "./assets/styles/reset.css";
@import "./assets/styles/bootstrap/bootstrap-grid.min.css";
@import "./assets/styles/tirscript/style.css";
@import "./assets/styles/apteka/style.css";
</style>