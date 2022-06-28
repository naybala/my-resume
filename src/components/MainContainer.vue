<template>
  <div v-if="loading">
    <Loader />
  </div>
  <div class="container ms-auto me-auto p-2" v-if="!loading">
    <div class="header-container">
      <h2>Mr. Nay Ba La</h2>
      <p class="fst-italic fw-bold fs-4">
        I'm Nay Ba La from where my bio as below _________>
      </p>
    </div>
    <div class="flex-container">
      <LeftContainer />
      <RightContainer />
    </div>
  </div>
</template>

<script>
import Loader from "./Loader.vue";
import LeftContainer from "./LeftContainer.vue";
import RightContainer from "./RightContainer.vue";
export default {
  components: {
    Loader,
    LeftContainer,
    RightContainer,
  },
  data: () => ({
    loading: true,
  }),
  mounted() {
    setTimeout(() => {
      this.loading = false;
    }, 2500);
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
