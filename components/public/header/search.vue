<template>
    <div class="search">
        <el-row>
            <el-col :span="6">
                <search-left></search-left>
            </el-col>
            <el-col :span="12">
                <search-center/>
            </el-col>
            <el-col :span="6">
                <search-right></search-right>
            </el-col>
        </el-row>
    </div>
</template>

<script>
import SearchLeft from './searchLeft'
import SearchCenter from './searchCenter'
import SearchRight from './searchRight'
export default {
    components:{
        SearchLeft,
        SearchCenter,
        SearchRight
    }
}
</script>