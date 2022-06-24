<template>
  <div class="container ms-auto me-auto p-2">
    <div class="header-container">
      <h2>Mr. Nay Ba La</h2>
      <p class="fst-italic fw-bold fs-4">I'm Nay Ba La</p>
    </div>
    <div class="flex-container">
      <LeftContainer />
      <RightContainer />
    </div>
  </div>
</template>

<script>
import LeftContainer from "./LeftContainer.vue";
import RightContainer from "./RightContainer.vue";
export default {
  components: {
    LeftContainer,
    RightContainer,
  },
};
</script>

<style scoped>
.flex-container {
  display: flex;
  flex-wrap: wrap;
}
.header-container {
  margin-left: 1rem;
}
</style>
