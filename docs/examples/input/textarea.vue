<template>
  <el-input
    v-model="textarea"
    style="width: 120px"
    :rows="2"
    type="textarea"
    placeholder="Please input"
  />
</template>

<script lang="ts" setup>
import { ref } from 'vue'

const textarea = ref('')
</script>
