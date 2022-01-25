<template>
  <div class="horizontal-list horizontal-list-container">
    <ul class="horizontal-list__header-list">
      <li class="horizontal-list__item">
        <a class="horizontal-list__link" href="">Demos</a>
      </li>
      <li class="horizontal-list__item">
        <a class="horizontal-list__link" href="">Pages</a>
      </li>
      <li class="horizontal-list__item">
        <a class="horizontal-list__link" href="">Support</a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "HorizontalList",
};
</script>


<style scoped>
/* .horizontal-list-container {
  width: 217px;
  height: 20px;
} */
.horizontal-list__header-list {
  height: 20px; /*Zdublowane wysokośći, jak to rozwiązać? */
  width: 217px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.horizontal-list__link {
  color: #c4c4c4;
  font-family: Circular Std Book;
  font-size: 16px;
  font-weight: 450;
}
.horizontal-list__link:hover {
  transition: 0.2s;
  color: #fff;
}
</style>