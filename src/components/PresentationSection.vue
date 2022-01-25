<template>
  <div class="presentation-main-container">
    <div class="presentation-main-container__title">
      It's everything you'll ever need
    </div>
    <div class="presentation-main-container__row">
      <div class="presentation-main-container__row-1">
        <div class="presentation-main-container__brick">
          <div
            class="
              presentation-main-container__brick--icon
              presentation-main-container__brick--icon-orange
            "
          >
            <img
              class="presentation-main-container__brick--icon-mobile"
              src="@/assets/img/SmartphoneIcon.svg/"
            />
          </div>
          <p class="presentation-main-container__brick--txt">
            50+ Unique Design Blocks
          </p>
        </div>
        <div class="presentation-main-container__brick">
          <div
            class="
              presentation-main-container__brick--icon
              presentation-main-container__brick--icon-blue
            "
          >
            <img
              class="presentation-main-container__brick--icon-mobile"
              src="@/assets/img/SmartphoneIcon.svg/"
            />
          </div>
          <p class="presentation-main-container__brick--txt">
            Multiple Layouts
          </p>
        </div>
        <div class="presentation-main-container__brick">
          <div
            class="
              presentation-main-container__brick--icon
              presentation-main-container__brick--icon-yellow
            "
          >
            <img
              class="presentation-main-container__brick--icon-mobile"
              src="@/assets/img/SmartphoneIcon.svg/"
            />
          </div>
          <p class="presentation-main-container__brick--txt">
            Mobile First Design
          </p>
        </div>
      </div>
      <div class="presentation-main-container__row-2">
        <div class="presentation-main-container__brick">
          <div
            class="
              presentation-main-container__brick--icon
              presentation-main-container__brick--icon-blue
            "
          >
            <img
              class="presentation-main-container__brick--icon-mobile"
              src="@/assets/img/SmartphoneIcon.svg/"
            />
          </div>
          <p class="presentation-main-container__brick--txt">
            Fully Responsive
          </p>
        </div>

        <div class="presentation-main-container__brick">
          <div
            class="
              presentation-main-container__brick--icon
              presentation-main-container__brick--icon-orange
            "
          >
            <img
              class="presentation-main-container__brick--icon-mobile"
              src="@/assets/img/SmartphoneIcon.svg/"
            />
          </div>
          <p class="presentation-main-container__brick--txt">
            Bootstrap 4 Framework
          </p>
        </div>
      </div>
      <div class="presentation-main-container__row-3">
        <div class="presentation-main-container__brick">
          <div
            class="
              presentation-main-container__brick--icon
              presentation-main-container__brick--icon-green
            "
          >
            <img
              class="presentation-main-container__brick--icon-mobile"
              src="@/assets/img/SmartphoneIcon.svg/"
            />
          </div>
          <p class="presentation-main-container__brick--txt">Humanly Support</p>
        </div>
        <div class="presentation-main-container__brick">
          <div
            class="
              presentation-main-container__brick--icon
              presentation-main-container__brick--icon-orange
            "
          >
            <img
              class="presentation-main-container__brick--icon-mobile"
              src="@/assets/img/SmartphoneIcon.svg/"
            />
          </div>

          <p class="presentation-main-container__brick--txt">
            Lifetime Updates
          </p>
        </div>
        <div class="presentation-main-container__brick">
          <div
            class="
              presentation-main-container__brick--icon
              presentation-main-container__brick--icon-blue
            "
          >
            <img
              class="presentation-main-container__brick--icon-mobile"
              src="@/assets/img/SmartphoneIcon.svg/"
            />
          </div>
          <p class="presentation-main-container__brick--txt">
            Rich Documentation
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "PresentationSection",
  components: {},
};
</script>

<style scoped>
.presentation-main-container {
  display: flex;
  margin-top: 165px;
  flex-direction: column;
  width: 1400px;
  height: 744px;
  background-color: rgba(65, 62, 101, 1);
}
.presentation-main-container__title {
  font-family: Circular Std Book;
  font-weight: 700;
  font-size: 60px;
  line-height: 70px;
  letter-spacing: -1px;
  width: 509px;
  height: 140p;
  color: #fff;
  margin-top: 100px;
  margin-left: 446px;
  text-align: center;
}
.presentation-main-container__row {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-self: center;
  width: 1104px;
  height: 308px;
  margin-top: 72px;
}
.presentation-main-container__row-1,
.presentation-main-container__row-3 {
  display: flex;
  justify-content: space-between;
  flex-direction: row;
  width: 1104px;
  height: 80px;
}
.presentation-main-container__row-2 {
  display: flex;
  justify-content: space-between;
  flex-direction: row;
  width: 729px;
  height: 80px;
  margin-left: 93px;
}
.presentation-main-container__brick {
  display: flex;
  align-items: center;
  width: 348px;
  height: 80px;
  border: 1px solid rgba(234, 233, 242, 1);
  border-radius: 10px;
  background-color: #fff;
}
.presentation-main-container__brick--icon {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 55px;
  height: 55px;
  border-radius: 50%;
  align-self: center;
  margin-left: 15px;
}
.presentation-main-container__brick--icon-orange {
  background-color: rgba(240, 64, 55, 0.0972);
}
.presentation-main-container__brick--icon-blue {
  background-color: rgba(84, 84, 212, 0.1);
}
.presentation-main-container__brick--icon-yellow {
  background-color: rgba(254, 220, 90, 0.1);
}
.presentation-main-container__brick--icon-green {
  background-color: rgba(119, 191, 65, 0.1);
}
.presentation-main-container__brick--txt {
  font-family: Circular Std Book;
  font-size: 21px;
  font-weight: 700;
  letter-spacing: -0.66px;
  line-height: 26px;
  margin-left: 15px;
}
</style>