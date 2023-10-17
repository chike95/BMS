<template>
  <div class="common-layout">
    <el-container>
      <el-aside>
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
.el-aside {
  width: 200px;
  height: 100vh;
  background-color: #be1313;
}

.el-header {
  height: 76px;
  position: relative;
  text-align: right;
  background-color: var(--el-color-primary-light-7);
  color: var(--el-text-color-primary);
}

.el-main {
  background-color: #7b7ac9;
}
</style>
