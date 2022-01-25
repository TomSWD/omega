<template>
  <div class="hero-right-container">
    <h3 class="hero-right-container__title">
      Enjoy every single beat on headphone!
    </h3>
    <p class="hero-right-container__txt">
      For Iphone, iPad, and Android users, be sure your product's firmware is up
      to date throught the Bose connect app.
    </p>
    <div class="hero-right-container__price">
      <div class="hero-right-container__price--299">$299</div>
      <div class="hero-right-container__price--save">Save 30% today</div>
      <div class="hero-right-container__price--399">Original price $399</div>
    </div>
    <div class="hero-right-container__counter">
      <form>
        <input
          class="hero-counter"
          id="cart"
          name="cart"
          type="number"
          step="1"
          min="0"
        />
      </form>
    </div>
    <Button :text="'Add to cart'" />
  </div>
</template>

<script>
import Button from "./Ui/Button.vue";

export default {
  name: "HeroMainRight",
  components: {
    Button,
  },
};
</script>

<style scoped>
.hero-right-container {
  width: 596px;
  height: 479px;
  margin-top: 135px;
  margin-left: -55px;
}
.hero-right-container__title {
  font-family: Circular Std Book;
  color: #fff;
  font-size: 60px;
  font-weight: 700;
  line-height: 70px;
}
.hero-right-container__txt {
  font-family: Circular Std Book;
  color: rgba(196, 196, 196, 1);
  font-weight: 450;
  font-size: 21px;
  line-height: 39px;
  margin-top: 15px;
}
.hero-right-container__price {
  display: flex;
  flex-direction: column;
  width: 322px;
  height: 131px;
  background-color: rgba(101, 101, 233, 1);
  border-radius: 10px;
  margin-top: 30px;
}
.hero-right-container__price--299 {
  font-family: Circular Std Book;
  color: #fff;
  font-size: 58px;
  font-weight: 700;
  margin-left: 23px;
  margin-top: 21px;
}
.hero-right-container__price--save {
  display: flex;
  width: 135px;
  height: 38px;
  font-family: Circular Std Book;
  color: #fff;
  font-size: 16px;
  font-weight: 400;
  padding-top: 11px;
  padding-left: 11px;
  background-color: rgba(119, 191, 65, 1);
  border-radius: 5px;
  margin-left: 167px;
  margin-top: -48px;
}
.hero-right-container__price--399 {
  font-family: Circular Std Book;
  color: rgba(255, 255, 255, 0.7);
  font-size: 21px;
  margin-left: 23px;
  margin-top: 23px;
}
.hero-counter {
  width: 91px;
  height: 60px;
  margin-top: 20px;
  border-radius: 5px;
  font-size: 50px;
  text-align: center;
}
</style>