<template>
  <div class="hello">
    <button @click="isHidden = !isHidden">
      {{ isHidden ? "Show Message" : "Hide Message" }}
    </button>

    <h1 v-if="!isHidden">{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: "DisplayPage",
  props: {
    msg: String,
  },
  data() {
    return {
      isHidden: false,
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
</style>
