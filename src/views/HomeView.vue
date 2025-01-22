<template>
  <div class="row">
    <div class="col-2"></div>

    <div class="col-7">
      <br />
      <Card />
    </div>

    <div class="col-3">... ovdje ide desni stupac!</div>
  </div>
</template>

<script>
// @ is an alias to /src
import Card from "@/components/Card.vue";

export default {
  name: "HomeView",
  components: {
    Card,
  },
};
</script>
