<template>
  <div>
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

</style>
