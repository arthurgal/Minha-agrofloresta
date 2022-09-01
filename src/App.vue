<template>
  <div class="principal">
    <HelloWorld/>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import HelloWorld from "./components/HelloWorld.vue";

export default defineComponent({
  components: { HelloWorld },
  name: "App",
});
</script>

<style>
  body{
    padding: 0;
    margin: 0;
  }
  .principal{
    text-align: center;
    background-color: rgb(28, 28, 28);
    color: rgb(238, 238, 238);
    padding: 1rem;
  }
</style>
