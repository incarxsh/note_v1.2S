<template>
    <div class="app">
        <div class="header">
            <h2 class="h2">程序员笔记在线版</h2>
        </div>
        <div class="cont">
            <div class="left"></div>
            <div class="content"></div>
            <ueditor></ueditor> 
        </div>
    </div>
</template>

<script>
import ueditor from "@/components/common/ueditor"
export default {
    data() {
        return {
            
        }
    },
    mounted() {
        
    },
    components:{
        ueditor
    }
}
</script>

<style lang="less" scoped>

</style>
