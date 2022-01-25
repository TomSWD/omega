<template>
  <div class="info-section-left-container">
    <h3 class="info-section-left-container__title">
      Get noise free sound everytime
    </h3>
    <p class="info-section-left-container__txt">
      Create custom landing pages with Omega that converts more visitors than
      any website. With lots of unique blocks, you can easily build a page
      without coding.
    </p>
    <div class="info-section-left-container__design-1">
      <div class="design-1-icon">
        <img
          class="design-1-icon__input-1"
          src="@/assets/img/SectionIcon1.png"
        />
        <img
          class="design-1-icon__input-2"
          src="@/assets/img/SectionIcon2svg.svg"
        />
      </div>
      <div class="design-1-txt">
        <p class="design-1-txt__bold">50+ Unique Design Blocks</p>
        <br />
        <p class="design-1-txt__thin">with Carefully Coded</p>
      </div>
    </div>
    <div class="info-section-left-container__design-2">
      <div class="design-2-icon">
        <img
          class="design-2-icon__input-3"
          src="@/assets/img/SmartphoneIcon.svg"
        />
      </div>
      <div class="design-2-txt">
        <p class="design-2-txt__bold">Mobile First Design</p>
        <br />
        <p class="design-2-txt__thin">on Every Devices</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "InfoSectionLeft",
};
</script>

<style scoped>
.info-section-left-container {
  width: 516.35px;
  height: 512px;
}
.info-section-left-container__title {
  font-family: Circular Std Book;
  color: rgba(25, 25, 27, 1);
  font-size: 60px;
  font-weight: 700;
  line-height: 70px;
  letter-spacing: -1.88px;
  font-weight: bold;
  font-size: 60px;
  line-height: 70px;
  letter-spacing: -1.87579px;
}
.info-section-left-container__txt {
  font-family: Circular Std Book;
  color: rgba(105, 104, 113, 1);
  font-weight: 450;
  font-size: 21px;
  line-height: 39px;
  margin-top: 20px;
  letter-spacing: -0.66px;
}
.info-section-left-container__design-1,
.info-section-left-container__design-2 {
  display: flex;
  width: 359px;
  height: 95px;
  border: 1px solid rgba(234, 233, 242, 1);
  border-radius: 10px;
}
.info-section-left-container__design-1 {
  margin-top: 40px;
}
.info-section-left-container__design-2 {
  margin-top: 14px;
}
.design-1-icon {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 55px;
  height: 55px;
  background-color: rgba(240, 64, 55, 0.0972);
  border-radius: 50%;
  align-self: center;
  margin-left: 20px;
}
.design-1-icon__input-1 {
  margin-bottom: 8px;
}
.design-1-icon__input-2 {
  margin-top: 4px;
  margin-left: -6px;
}
.design-1-txt,
.design-2-txt {
  font-family: Circular Std Book;
  align-self: center;
  margin-left: 20px;
  margin-bottom: 6px;
}
.design-2-icon {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 55px;
  height: 55px;
  background-color: rgba(84, 84, 212, 0.1);
  border-radius: 50%;
  align-self: center;
  margin-left: 20px;
}
.design-1-txt__bold,
.design-2-txt__bold {
  font-family: Circular Std Book;
  font-size: 21px;
  font-weight: 700;
  letter-spacing: -0.66px;
}
.design-1-txt__thin,
.design-2-txt__thin {
  font-family: Circular Std Book;
  color: rgba(105, 104, 113, 1);
  font-size: 21px;
  font-weight: 500;
  line-height: 2px;
  letter-spacing: -0.66px;
}
</style>