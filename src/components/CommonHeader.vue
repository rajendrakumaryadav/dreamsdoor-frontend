<template>
  <nav-bar />
  <div class="container">
    <h1>{{ pageName }}</h1>
  </div>
</template>

<script>
import NavBar from "@/components/NavBar";

export default {
  name: "CommonHeader",
  components: { NavBar },
  props: {
    pageName: {
      String,
      required: true,
    },
  },
};
</script>

<style scoped>
.container {
  margin-top: auto;
}
</style>
