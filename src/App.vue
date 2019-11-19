<template>
  <div id="app">
    <div id="nav">
      <!-- <router-link> 默认渲染为 <a> 标签，但更好用 -->
      <router-link to="/dashboard/analysis">dashboard</router-link>|
      <router-link to="/form">form</router-link>
    </div>
    <router-view />
  </div>
</template>

<style lang="less"></style>
