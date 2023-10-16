<template>
  <div class="common-layout">
    <el-container>
      <el-aside width="200px">
        <Sidebar></Sidebar>
      </el-aside>

      <el-container>
        <el-header>
          <CommonHeader></CommonHeader>
        </el-header>
        <el-main>
          <router-view></router-view>
        </el-main>
      </el-container>
    </el-container>
  </div>
</template>

<script setup>
import CommonHeader from '@/components/CommonHeader.vue';
import Sidebar from '@/components/Sidebar.vue';

</script>

<style scoped>
* {
  margin: 0;
  padding: 0;
}

body,
html {
  margin: 0;
  padding: 0;
}

.el-aside {
  height: 100vh;
  background-color: #be1313;
}

.el-header {
  height: 76px;
  background-color: #17ce63;
}

.el-main {
  background-color: #7b7ac9;
}</style>
