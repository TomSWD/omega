<template>
  <div class="info-section-container">
    <InfoSectionLeft />
    <InfoSectionRight />
  </div>
</template>

<script>
import InfoSectionLeft from "./InfoSectionLeft.vue";
import InfoSectionRight from "./InfoSectionRight.vue";

export default {
  name: "InfoSection",
  components: {
    InfoSectionLeft,
    InfoSectionRight,
  },
};
</script>


<style scoped>
.info-section-container {
  display: flex;
  width: 1152px;
  height: 525px;
  margin: auto;
  margin-top: 135px;
}
</style>