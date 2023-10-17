<template>
    <el-menu :default-openeds="['1', '4']">
        <el-sub-menu index="1">
            <template #title>
                <el-icon>
                    <View />
                </el-icon>实时监测
            </template>
            <el-menu-item index="1-1">总览</el-menu-item>
            <el-menu-item index="1-2">应力应变</el-menu-item>
            <el-menu-item index="1-3">加速度</el-menu-item>
            <el-menu-item index="1-3">倾斜</el-menu-item>
        </el-sub-menu>
        <el-sub-menu index="2">
            <template #title>
                <el-icon>
                    <Timer />
                </el-icon>数据回放
            </template>
            <el-menu-item index="1-1">总览</el-menu-item>
            <el-menu-item index="1-2">应力应变</el-menu-item>
            <el-menu-item index="1-3">加速度</el-menu-item>
            <el-menu-item index="1-3">倾斜</el-menu-item>
        </el-sub-menu>
        <el-sub-menu index="3">
            <template #title>
                <el-icon>
                    <View />
                </el-icon>实时监测
            </template>
            <el-menu-item index="1-1">总览</el-menu-item>
            <el-menu-item index="1-2">应力应变</el-menu-item>
            <el-menu-item index="1-3">加速度</el-menu-item>
            <el-menu-item index="1-3">倾斜</el-menu-item>
        </el-sub-menu>
        <el-sub-menu index="4">
            <template #title>
                <el-icon>
                    <Timer />
                </el-icon>数据回放
            </template>
            <el-menu-item index="1-1">总览</el-menu-item>
            <el-menu-item index="1-2">应力应变</el-menu-item>
            <el-menu-item index="1-3">加速度</el-menu-item>
            <el-menu-item index="1-3">倾斜</el-menu-item>
        </el-sub-menu>
    </el-menu>
</template>

<style scoped>
.el-menu {
    background-color: #90b920;

}
</style>