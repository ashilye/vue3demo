<template>
  <div>
    <h1>{{ title }}</h1>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component'

@Options({
  props: {
    title: String
  }
})
export default class CommonHeader extends Vue {
  title!: string
}
</script>

<style lang="scss" scoped>

</style>
