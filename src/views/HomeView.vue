<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to my Vue.js app deployed to AWS S3" />
  </div>
</template>

<script lang="ts">
import HelloWorld from "@/components/HelloWorld.vue"; // @ is an alias to /src
import { defineComponent } from "vue";

export default defineComponent({
  name: "HomeView",
  components: {
    HelloWorld,
  },
});
</script>
