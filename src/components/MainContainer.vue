<template>
  <div class="container-col-md-10 text-center mt-5">
    <div class="row">
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
