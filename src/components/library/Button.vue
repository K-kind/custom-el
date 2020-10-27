<template>
  <el-button v-bind="$attrs" :round="round">my<slot /></el-button>
</template>
<script>
export default {
  props: {
    round: Boolean
  }
}
</script>
