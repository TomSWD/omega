<template>
  <a class="button button-cart">{{ text }}</a>
</template>

<script>
export default {
  name: "Button",
  props: {
    text: { type: String, required: true },
  },
};
</script>


<style scoped>
.button {
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
  margin-top: -60px;
  margin-left: 111px;
}

.button:hover {
  transition: 0.2s;
  background-color: #f0c931;
}
</style>