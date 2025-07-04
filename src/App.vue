<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue' // 引入 HelloWorld 组件
</script>

<template>
  <div> <!-- 容器元素 -->
    <a href="https://vite.dev" target="_blank"> <!-- 跳转到 Vite 官网的新标签页链接 -->
      <img src="/vite.svg" class="logo" alt="Vite logo" /> <!-- Vite logo 图片 -->
    </a>
    <a href="https://vuejs.org/" target="_blank"> <!-- 跳转到 Vue 官网的新标签页链接 -->
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" /> <!-- Vue logo 图片 -->
    </a>
  </div>
  <HelloWorld msg="Vite + Vue" /> <!-- 使用 HelloWorld 组件并传递 msg 属性 -->
  <!-- 更新提交 -->
</template>

<style scoped>
.logo {
  height: 6em; /* 设置高度为 6 个字体单位 */
  padding: 1.5em; /* 设置内边距为 1.5 个字体单位 */
  will-change: filter; /* 优化浏览器对滤镜变化的渲染性能 */
  transition: filter 300ms; /* 滤镜过渡效果，持续 300 毫秒 */
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa); /* 鼠标悬浮时添加蓝紫色阴影 */
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa); /* 鼠标悬浮 Vue logo 时添加绿色阴影 */
}
</style>
