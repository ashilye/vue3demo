<template>
  <div class="login-container">
    <el-button v-on:click="login">登录</el-button>
  </div>
</template>

<script lang="ts">
import { useRouter } from 'vue-router'

export default {
  setup () {
    const router = useRouter()
    const login = () => {
      router.push('/home')
    }

    return {
      login
    }
  }
}
</script>

<style lang="scss" scoped>

</style>
