<template>
  <div class="home-container">
    <CommonHeader title="头部标题"/>
    <CopyrightFooter content="footer"/>
  </div>
</template>

<script lang="ts">
import CommonHeader from '@/components/header/CommonHeader.vue'
import CopyrightFooter from '@/components/footer/CopyrightFooter.vue'
export default {
  components: {
    CommonHeader,
    CopyrightFooter
  }
}
</script>

<style lang="scss" scoped>

</style>
