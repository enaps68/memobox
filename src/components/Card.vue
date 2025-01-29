<template>
  <div class="card">
    <div id="header" class="card-header">dd/mm/yyyy</div>
    <img
      :src="info"
      class="card-img-top"
      alt="..."
      style="max-height: 500px; max-width: 500px; margin: auto"
    />
    <div class="card-body">
      <p class="card-text">
        Some quick example text to build on the card title and make up the bulk
        of the card's content.
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: "Card",
  props: ["info"],
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss"></style>
