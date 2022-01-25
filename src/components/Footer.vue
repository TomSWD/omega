<template>
  <div class="footer-main-container">
    <a class="omega-black" href="#"><img src="./Ui/OmegaBlack.svg" /></a>
    <div class="footer-main-container__mid-section">
      <a class="footer-link" href="#">Support</a>
      <a class="footer-link" href="#">Privacy Policy</a>
      <a class="footer-link" href="#">Terms and Conditions</a>
    </div>
    <div class="footer-main-container__copyright">
      © 2020 UXTheme, All Rights Reserved
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer",
  components: {},
};
</script>

<style scoped>
.footer-main-container {
  display: flex;
  justify-content: space-between;
  flex-direction: row;
  align-items: center;
  width: 1111px;
  height: 38px;
  margin: auto;
  margin-top: 34px;
  margin-bottom: 34px;
}
.footer-main-container__mid-section {
  display: flex;
  justify-content: space-between;
  width: 488px;
  height: 38px;
  padding-left: 55px;
  padding-right: 55px;
  font-family: Circular Std Book;
  font-weight: 450;
  font-size: 16px;
  line-height: 38px;
  margin-left: 170px;
}
.footer-link:hover {
  transition: 0.2s;
  opacity: 0.5;
}
.footer-main-container__copyright {
  display: flex;
  width: 285px;
  height: 38px;
  font-family: Circular Std Book;
  font-weight: 450;
  font-size: 16px;
  line-height: 38px;
  letter-spacing: -0.5px;
  justify-content: flex-end;
}
.omega-black:hover {
  transition: 0.2s;
  opacity: 0.5;
}
</style>