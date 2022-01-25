<template>
  <div class="try-main-container">
    <div class="try-main-container__left">
      <div class="try-main-container__left--title">
        2k+ people are <br />
        using this headset
        <div class="try-main-container__left--txt">
          Create custom landing pages with Omega that converts<br />
          more visitors than any website. With lots of unique<br />
          blocks, you can easily build a page without coding.
        </div>
        <div class="try-main-container__left--btn">Try it now</div>
      </div>
    </div>
    <img class="try-main-container__img" src="@/assets/img/TrySectionImg.png" />
  </div>
</template>

<script>
export default {
  name: "TrySection",
  components: {},
};
</script>

<style scoped>
.try-main-container {
  display: flex;
  width: 1400px;
  height: 790px;
  background-color: rgba(84, 84, 212, 1);
  margin-top: 130px;
}
.try-main-container__left {
  display: flex;
  margin-top: 211px;
  margin-left: 128px;
  width: 521px;
  height: 385px;
  position: relative;
  z-index: 2;
}
.try-main-container__left--title {
  font-family: Circular Std Book;
  font-weight: 700;
  font-size: 60px;
  line-height: 70px;
  color: #fff;
}
.try-main-container__left--txt {
  font-family: Circular Std Book;
  font-weight: 450;
  font-size: 21px;
  line-height: 39px;
  letter-spacing: -0.66px;
  color: #fff;
  margin-top: 24px;
}
.try-main-container__left--btn {
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
  margin-top: 40px;
}

.try-main-container__left--btn:hover {
  transition: 0.2s;
  background-color: #f0c931;
}
.try-main-container__img {
  margin-left: 83px;
  position: absolute;
  z-index: 1;
  margin-left: 95px;
}
</style>