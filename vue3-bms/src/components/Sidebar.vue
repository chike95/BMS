<template>
    <h3 class="mb-2">结构健康监测系统</h3>
    <el-scrollbar>
        <SidebarMenu> </SidebarMenu>
    </el-scrollbar>
</template>

<script setup>
import SidebarMenu from '@/components/menus/SidebarMenu.vue';
</script>
<style scoped>
h3 {
    margin: 0;
    padding-top: 26px;
    height: 50px;
    text-align: center;
}
</style>