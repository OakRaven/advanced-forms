<template>
  <simple-form />
</template>

<script>
import SimpleForm from "./components/SimpleForm.vue";

export default {
  name: "App",
  components: {
    SimpleForm,
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
