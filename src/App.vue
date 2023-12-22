<script setup>
import { getCategoryAPI } from '@/api/test'
;async () => {
  const res = await getCategoryAPI()
  console.log(res)
}
</script>

<template>
  <el-button style="--el-button-bg-color: red">Primary</el-button>
  <el-button type="primary">Primary</el-button>
  <el-button type="warning">Waring</el-button>
</template>

<style scoped></style>
