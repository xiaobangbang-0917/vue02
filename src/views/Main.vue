<template>
    <div>
        <el-container>
            <el-aside width="200px">
                左侧菜单
                <CommonAside />
            </el-aside>
            <el-container>
                <el-header>Header</el-header>
                <el-main>
                    <router-view>Main</router-view>
                </el-main>
            </el-container>
        </el-container>
    </div>
</template>
<script>

import CommonAside from '../components/CommonAside.vue'

export default{
    data() {
        return {}
    },
    components:{
        CommonAside
    }
}
</script>
