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
    <br>
    <h2>Developed Projects</h2>
    <div >
      <LuxuraSpa/>
    </div>
    <br>
    <div >
      <RahtaEntertainment/>
    </div>
    <br>
    <div >
      <Arimadanapura/>
    </div>
    <br>
    <div >
      <GFMS/>
    </div>
    <br>
    <div >
      <GHRS/>
    </div>
  </div>
</template>

<script>
import Loader from "./Loader.vue";
import LeftContainer from "./LeftContainer.vue";
import RightContainer from "./RightContainer.vue";
import LuxuraSpa from "./LuxuraSpa.vue";
import RahtaEntertainment from "./RahtaEntertainment.vue";
import Arimadanapura from "./Arimadanapura.vue";
import GFMS from "./GFMS.vue";
import GHRS from "./GHRS.vue";
export default {
  components: {
    Loader,
    LeftContainer,
    RightContainer,
    LuxuraSpa,
    RahtaEntertainment,
    Arimadanapura,
    GFMS,
    GHRS 
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
