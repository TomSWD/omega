<template>
  <div class="content-main-container">
    <div class="content-main-container__title">Enjoy your music</div>
    <div class="content-main-container__txt">
      Create custom landing pages with Omega that converts more visitors<br />than
      any website. With lots of unique blocks, you can easily build a<br />
      page without coding.
    </div>
    <div class="content-main-container__pics">
      <img class="content-1" src="@/assets/img/Content1.png" />
      <img class="content-2" src="@/assets/img/Content2.png" />
    </div>
  </div>
</template>

<script>
export default {
  name: "ContentSection",
  components: {},
};
</script>

<style scoped>
.content-main-container {
  display: flex;
  align-items: center;
  flex-direction: column;
  width: 1110px;
  height: 789px;
  margin: auto;
  margin-top: 90px;
}
.content-main-container__title {
  font-family: Circular Std Book;
  font-weight: 700;
  font-size: 60px;
  line-height: 70px;
  letter-spacing: -1px;
}
.content-main-container__txt {
  text-align: center;
  font-family: Circular Std Book;
  font-weight: 450;
  font-size: 21px;
  line-height: 39px;
  letter-spacing: -0.6px;
  color: rgba(105, 104, 113, 1);
  margin-top: 20px;
}
.content-main-container__pics {
  display: flex;
  margin-left: 50px;
}
.content-1 {
  align-self: flex-start;
  margin-left: -50px;
  margin-top: 60px;
}
.content-2 {
  margin-top: 60px;
  margin-left: -80px;
}
</style>