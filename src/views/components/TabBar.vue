<template>
  <van-tabbar v-model="active">
    <van-tabbar-item name="home" icon="home-o">标签</van-tabbar-item>
    <van-tabbar-item name="search" icon="search">标签</van-tabbar-item>
    <van-tabbar-item name="friends" icon="friends-o">标签</van-tabbar-item>
    <van-tabbar-item name="setting" icon="setting-o">标签</van-tabbar-item>
  </van-tabbar>
</template>

<script setup>
import { ref } from 'vue'

const active = ref('home')
</script>

<style lang="scss" scoped></style>
