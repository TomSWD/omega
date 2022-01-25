<template>
  <div class="cta-main-container">
    <div class="cta-main-container__title">
      Enjoy every beat. <br />
      Get a new headphone.
    </div>
    <div class="cta-main-container__btn">Buy now</div>
  </div>
</template>

<script>
export default {
  name: "CtaSection",
  components: {},
};
</script>

<style scoped>
.cta-main-container {
  display: flex;
  background-color: rgba(84, 84, 212, 1);
  width: 1400px;
  height: 342px;
  margin-top: 110px;
}
.cta-main-container__title {
  font-family: Circular Std Book;
  color: #fff;
  font-size: 60px;
  font-weight: 700;
  line-height: 70px;
  letter-spacing: -1px;
  margin-left: 144px;
  align-self: center;
}
.cta-main-container__btn {
  display: flex;
  width: 200px;
  height: 60px;
  color: rgba(0, 0, 0, 0.788926);
  background-color: #fedc5a;
  font-family: Circular Std Medium;
  font-size: 21px;
  align-items: center;
  justify-content: center;
  border: 1px solid #f0c931;
  border-radius: 5px;
  cursor: pointer;
  align-self: center;
  margin-left: 300px;
}
.cta-main-container__btn:hover {
  transition: 0.2s;
  background-color: #f0c931;
}
</style>