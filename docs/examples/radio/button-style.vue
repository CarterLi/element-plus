<template>
  <div>
    <el-radio-group v-model="radio1" size="large">
      <el-radio-button label="New York" />
      <el-radio-button label="Washington" />
      <el-radio-button label="Los Angeles" />
      <el-radio-button label="Chicago" />
    </el-radio-group>
  </div>
  <div style="margin-top: 20px">
    <el-radio-group v-model="radio2">
      <el-radio-button label="New York" />
      <el-radio-button label="Washington" />
      <el-radio-button label="Los Angeles" />
      <el-radio-button label="Chicago" />
    </el-radio-group>
  </div>
  <div style="margin-top: 20px">
    <el-radio-group v-model="radio3" size="small">
      <el-radio-button label="New York" />
      <el-radio-button label="Washington" disabled />
      <el-radio-button label="Los Angeles" />
      <el-radio-button label="Chicago" />
    </el-radio-group>
  </div>
  <div style="margin-top: 20px; display: flex">
    <el-radio-button v-model="radio4" label="New York" />
    <el-radio-button
      v-model="radio4"
      style="margin-left: 10px"
      label="Washington"
    />
    <el-radio-button
      v-model="radio4"
      style="margin-left: 10px"
      label="Los Angeles"
    />
    <el-radio-button
      v-model="radio4"
      style="margin-left: 10px"
      label="Chicago"
    />
  </div>
  <div style="margin-top: 20px; display: flex">
    <el-radio-button v-model="radio5" size="small" label="New York" />
    <el-radio-button
      v-model="radio5"
      size="small"
      style="margin-left: 10px"
      label="Washington"
    />
    <el-radio-button
      v-model="radio5"
      size="small"
      style="margin-left: 10px"
      label="Los Angeles"
    />
    <el-radio-button
      v-model="radio5"
      size="small"
      style="margin-left: 10px"
      label="Chicago"
    />
  </div>
</template>

<script lang="ts" setup>
import { ref } from 'vue'

const radio1 = ref('New York')
const radio2 = ref('New York')
const radio3 = ref('New York')
const radio4 = ref('New York')
const radio5 = ref('New York')
</script>
