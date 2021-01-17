<template>
  <div></div>
</template>
<script src="https://cdn.jsdelivr.net/npm/vue/dist/vue.js"></script>
<script>
export default {};
var app = new Vue({
  el: "#app",
  data: {
    message: "Hello Vue!"
  }
});
// 定义一个名为 button-counter 的新组件
Vue.component("button-counter", {
  data: function() {
    return {
      count: 0
    };
  },
  template:
    '<button v-on:click="count++">You clicked me {{ count }} times.</button>'
});
</script>

<style lang="scss" scoped>
</style>
