<template>
    <div class="footer-container">
      <img src="@/assets/images/login/hyn.jpg"/>
      <h3>Copyright © 2020 豫ICP备18006204号-1</h3>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component'

@Options({
  props: {
    content: String
  }
})

export default class CopyrightFooter extends Vue {
  content!: string
}
</script>

<style lang="scss" scoped>
.footer-container {
  text-align: center;
  position: absolute; //绝对定位
  left: 50%;
  bottom: 0;
  transform: translate(-50%, -50%);
  > h3{
    //上内边距
    //右内边距
    //下内边距
    //左内边距
    padding: 10px;
  }
}
</style>
