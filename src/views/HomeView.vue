<template>
  <home-header />
  <div class="container">
    <div class="top-30">
      <p>Home Page</p>
    </div>
  </div>
</template>

<script>
import HomeHeader from "@/components/HomeHeader";

export default {
  name: "HomeView",
  components: {
    HomeHeader,
  },
};
</script>
