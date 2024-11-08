<script lang="ts" setup>
import { isDark } from '~/composables/dark'
</script>

<template>
  <div>
    <el-button color="#2D5AFF" :dark="isDark">Default</el-button>
    <el-button color="#2D5AFF" :dark="isDark" plain>Plain</el-button>

    <el-button color="#2D5AFF" :dark="isDark" disabled>Disabled</el-button>
    <el-button color="#2D5AFF" :dark="isDark" disabled plain>
      Disabled Plain
    </el-button>
  </div>
</template>
