<template>
  <div class="hero-container">
    <OmegaSvg />
    <HorizontalList class="hero__horizontal-list-container" />
    <div class="hero__cart-container">
      <div class="hero__cart-container--text">Cart</div>
      <div class="hero__cart-container--button">3</div>
    </div>
  </div>
</template>

<script>
import HorizontalList from "./Ui/HorizontalList.vue";
import OmegaSvg from "./Ui/OmegaSvg.vue";

export default {
  name: "Hero",
  components: {
    HorizontalList,
    OmegaSvg,
  },
};
</script>

<style scoped>
.hero-container {
  position: relative;
  top: 54px;
  margin-left: 55px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  width: 1349px;
  height: 31px;
}
.hero__cart-container {
  display: flex;
  align-items: center;
  justify-content: space-between;
  width: 73px;
  height: 28px;
  margin-right: 61px;
}
.hero__cart-container--text {
  font-family: Circular Std Book;
  color: #fff;
  font-weight: 450;
}
.hero__cart-container--button {
  color: rgba(0, 0, 0, 0.7889);
  font-family: Circular Std Book;
  font-weight: 500;
  font-size: 16px;
  background-color: #fedc5a;
  border-radius: 50%;
  width: 28px;
  height: 28px;
  line-height: 28px;
  text-align: center;
}
</style>