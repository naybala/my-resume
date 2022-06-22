<template>
  <div class="header-container">
    <h2>Mr. Nay Ba La</h2>
    <p>I'm Nay Ba La</p>
  </div>
  <div class="flex-container">
    <LeftContainer />
    <RightContainer />
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
  margin-left: 20rem;
  margin-right: 20rem;
}
.header-container {
  margin-top: 3rem;
  margin-left: 20rem;
}
</style>
