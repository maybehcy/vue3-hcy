<template>
  <div class="app">
    <div>{{ $store.state.name }}</div>
    <router-link to="/login">登录</router-link>
    <router-link to="/main">首页</router-link>
    <router-view></router-view>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue"

export default defineComponent({
  name: "App"
})
</script>

<style lang="less">
.app {
  color: red;
}
</style>
