<template>
  <div class="hero-main-container">
    <HeroMainLeft />
    <HeroMainRight />
  </div>
</template>

<script>
import HeroMainLeft from "./HeroMainLeft.vue";
import HeroMainRight from "./HeroMainRight.vue";

export default {
  name: "HeroMain",
  components: {
    HeroMainLeft,
    HeroMainRight,
  },
};
</script>

<style scoped>
.hero-main-container {
  display: flex;
  width: 1400px;
  height: 960px;
  background-color: rgba(84, 84, 212, 1);
  justify-content: center;
  align-items: center;
}
</style>