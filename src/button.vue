<template>
  <button class="my-button">{{ title }}</button>
</template>
<script>
export default {
  name: "MyButton",
  data() {
    return {
      title: "我的第一个组件库button",
    };
  },
};
</script>
<style scoped>
.my-button {
  color: red;
}
</style>
