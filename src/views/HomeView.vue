<template>
  <div class="home">
    <DisplayPage msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
// @ is an alias to /src
import DisplayPage from "@/components/DisplayPage.vue";

export default {
  name: "HomeView",
  components: {
    DisplayPage,
  },
};
</script>
