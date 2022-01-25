<template>
  <div class="testimonial-main-container">
    <div class="testimonial-main-container__title">What users say</div>
    <div class="testimonial-main-container__txt">
      Create custom landing pages with Omega that converts <br />
      more visitors than any website.
    </div>
    <div class="testimonial-main-container__ref-window">
      <div class="testimonial-main-container__left-ref-window">
        <div class="testimonial-main-container__left-ref-window--txt">
          OMG! I cannot believe that I have got a brand new landing page after
          getting Omega. It was super easy to edit and publish.
        </div>
        <div class="testimonial-main-container__ref-window--footer">
          <img src="@/assets/img/Oval-left.svg" />
          <div
            class="testimonial-main-container__ref-window--footer--signature"
          >
            <div
              class="
                testimonial-main-container__ref-window--footer--signature--head
              "
            >
              Jonathan Taylor
            </div>
            <div
              class="
                testimonial-main-container__ref-window--footer--signature--under-head
              "
            >
              CEO at Creativex
            </div>
          </div>
        </div>
      </div>
      <div class="testimonial-main-container__right-ref-window">
        <div class="testimonial-main-container__right-ref-window--txt">
          OMG! I cannot believe that I have got a brand new landing page after
          getting Omega. It was super easy to edit and publish.
        </div>
        <div class="testimonial-main-container__ref-window--footer">
          <img src="@/assets/img/Oval-right.svg" />
          <div
            class="testimonial-main-container__ref-window--footer--signature"
          >
            <div
              class="
                testimonial-main-container__ref-window--footer--signature--head
              "
            >
              Marie Stanley
            </div>
            <div
              class="
                testimonial-main-container__ref-window--footer--signature--under-head
              "
            >
              Digital Marketer, Writer
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="testimonial-main-container__slider">
      <a href="/" class="testimonial-main-container__slider--active" />
      <a href="/" class="testimonial-main-container__slider--no-active" />
      <a href="/" class="testimonial-main-container__slider--no-active" />
    </div>
  </div>
</template>

<script>
export default {
  name: "Testimonial",
  components: {},
};
</script>

<style scoped>
.testimonial-main-container {
  display: flex;
  flex-direction: column;
  justify-content: center;
  font-family: Circular Std Book;
  width: 946px;
  height: 545px;
  margin: auto;
  margin-top: 90px;
}
.testimonial-main-container__title {
  font-size: 60px;
  font-weight: 700;
  line-height: 70px;
  letter-spacing: -2;
  color: #19191b;
  align-self: center;
}
.testimonial-main-container__txt {
  font-weight: 450;
  font-size: 21px;
  line-height: 39px;
  letter-spacing: -0.66;
  color: rgba(105, 104, 113, 1);
  text-align: center;
  margin-top: 15px;
}
.testimonial-main-container__ref-window {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}
.testimonial-main-container__left-ref-window,
.testimonial-main-container__right-ref-window {
  display: flex;
  flex-direction: column;
  width: 458px;
  height: 252px;
  border: 1px solid rgba(234, 233, 242, 1);
  border-radius: 10px;
  margin-top: 60px;
}
.testimonial-main-container__left-ref-window--txt,
.testimonial-main-container__right-ref-window--txt {
  width: 403px;
  height: 117px;
  font-weight: 400;
  font-size: 19px;
  line-height: 39px;
  letter-spacing: -2;
  margin-top: 25px;
  margin-left: 33px;
}
.testimonial-main-container__ref-window--footer {
  display: flex;
  width: 230px;
  height: 50px;
  margin-left: 33px;
  margin-top: 35px;
}
.testimonial-main-container__ref-window--footer--signature {
  display: flex;
  flex-direction: column;
}
.testimonial-main-container__ref-window--footer--signature--head {
  font-size: 21px;
  font-weight: 700;
  line-height: 28px;
  letter-spacing: -0.66;
  margin-left: 15px;
}
.testimonial-main-container__ref-window--footer--signature--under-head {
  font-weight: 450;
  font-size: 16px;
  line-height: 28px;
  letter-spacing: -0.5;
  color: rgba(105, 104, 113, 1);
  margin-top: -5px;
  margin-left: 15px;
}
.testimonial-main-container__slider {
  display: flex;
  flex-direction: row;
  align-self: center;
  justify-content: space-between;
  width: 100px;
  height: 8px;
  margin-top: 60px;
}
.testimonial-main-container__slider--active {
  width: 45px;
  height: 8px;
  border-radius: 4px;
  background-color: #5454d4;
  pointer-events: none;
}
.testimonial-main-container__slider--no-active {
  width: 17px;
  height: 8px;
  border-radius: 4px;
  background-color: #eae9f2;
}
.testimonial-main-container__slider--no-active:hover {
  transition: 0.2s;
  background-color: #c4c4c4;
}
</style>