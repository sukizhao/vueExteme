<template>
  <dx-button :text="text"/>
</template>
<script>
/*组件方式引用*/
import DxButton from "devextreme-vue/button";
export default {
  name: "HelloWorld",
  data() {
    return {
      text: "Hello!"
    };
  },
  components: {
    DxButton
  }
};
</script>

 <style lang="scss" scoped>
//  scoped 表示局部作用域
h1 {
  color: red;
}
.lunbotu {
  height: 300px;
}
</style>


