<template>
  <div class="row">
    <div class="col-2"></div>

    <div class="col-7">
      <br />
      <Card v-for="card in cards" :info="card" />
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
  data: function () {
    return {
      cards: [
        "https://picsum.photos/id/13/400/400",
        "https://picsum.photos/id/65/400/400",
        "https://picsum.photos/id/319/400/400",
      ],
    };
  },
};
</script>
