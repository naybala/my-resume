<template>
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
  margin-top: 5rem;
  margin-left: 20rem;
  margin-right: 20rem;
}
</style>
